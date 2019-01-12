#!/bin/sh
#
# An example hook script to check the commit log message taken by
# applypatch from an e-mail message.

. git-sh-setup
test -x "$GIT_DIR/hooks/commit-msg" &&
    exec "$GIT_DIR/hooks/commit-msg" ${1+"$@"}
: