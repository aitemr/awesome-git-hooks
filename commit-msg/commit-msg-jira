#!/usr/bin/env bash

# set this to your active development branch
develop_branch="develop"
current_branch="$(git rev-parse --abbrev-ref HEAD)"

# only check commit messages on main development branch
[ "$current_branch" != "$develop_branch" ] && exit 0

# regex to validate in commit msg
commit_regex='(wap-[0-9]+|merge)'
error_msg="Aborting commit. Your commit message is missing either a JIRA Issue ('WAP-1111') or 'Merge'"

if ! grep -iqE "$commit_regex" "$1"; then
    echo "$error_msg" >&2
    exit 1
fi