#!/bin/sh
# The hook is called with the following parameters:
#
# $1 -- the upstream the series was forked from.
# $2 -- the branch being rebased (or empty when rebasing the current branch).
#
branch="$2"
[ -n "$branch" ] || branch=$(git rev-parse --abbrev-ref HEAD)
lock="branch.${branch}.rebaselock"
if [ "$(git config --bool "$lock")" = true ]; then
echo "pre-rebase hook: \"$lock\" is set to true. Refusing to rebase."
exit 1
fi
