#!/bin/sh
#
# An example hook script to verify if you are on battery, in case you
# are running Linux or OS X. Called by git-gc --auto with no arguments.
# The hook should exit with non-zero status after issuing an appropriate
# message if it wants to stop the auto repacking.

if test -x /sbin/on_ac_power && /sbin/on_ac_power
then
	exit 0
elif test "$(cat /sys/class/power_supply/AC/online 2>/dev/null)" = 1
then
	exit 0
elif grep -q 'on-line' /proc/acpi/ac_adapter/AC/state 2>/dev/null
then
	exit 0
elif grep -q '0x01$' /proc/apm 2>/dev/null
then
	exit 0
elif grep -q "AC Power \+: 1" /proc/pmu/info 2>/dev/null
then
	exit 0
elif test -x /usr/bin/pmset && /usr/bin/pmset -g batt |
	grep -q "Currently drawing from 'AC Power'"
then
	exit 0
fi

echo "Auto packing deferred; not on AC"
exit 1