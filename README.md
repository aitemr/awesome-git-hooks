## Awesome Git Hooks  

[![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#)
[![@aitemr](https://img.shields.io/badge/contact-%40aitemr-brightgreen.svg)](https://t.me/aitemr)

> A curated list of awesome [Git hooks](https://git-scm.com/docs/githooks)

## About

Git Hooks are scripts that run automatically every time a particular event occurs in a Git repository.

## Contents

- [Useful Git Hooks scripts](#useful-git-hooks-scripts)
- [Tools](#tools)
- [Articles](#articles)
- [Support](#support)

## Useful Git Hooks scripts

- [pre-commit](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-commit) - This hook is called before obtaining the proposed commit message.
- [prepare-commit-msg](https://github.com/aitemr/awesome-git-hooks/tree/master/prepare-commit-msg) - Called after receiving the default commit message, just prior to firing up the commit message editor.
- [pre-receive](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-receive) - This is called on the remote repo just before updating the pushed refs.
- [commit-msg](https://github.com/aitemr/awesome-git-hooks/tree/master/commit-msg) - Can be used to adjust the message after it has been edited in order to ensure conformity to a standard or to reject based on any criteria.
- [pre-push](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-push) - Called prior to a push to a remote. In addition to the parameters, additional information, separated by a space is passed in through stdin in the form of `<local ref> <local sha1> <remote ref> <remote sha1>`.
- [pre-auto-gc](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-auto-gc) - Is used to do some checks before automatically cleaning repos. 
- [pre-rebase](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-rebase) - Called when rebasing a branch. Mainly used to halt the rebase if it is not desirable.
- [applypatch-msg](https://github.com/aitemr/awesome-git-hooks/tree/master/applypatch-msg) - Can edit the commit message file and is often used to verify or actively format a patch's message to a project's standards.
- [post-receive](https://github.com/aitemr/awesome-git-hooks/tree/master/post-receive) - This is run on the remote when pushing after the all refs have been updated. It does not take parameters, but receives info through stdin in the form of `<old-value> <new-value> <ref-name>`. 
- [post-rewrite](https://github.com/aitemr/awesome-git-hooks/tree/master/post-rewrite) - This is called when git commands are rewriting already committed data.

## Soon 🙈

- [pre-applypatch]() - This is actually called after the patch is applied, but before the changes are committed.
- [post-applypatch]() - This hook is run after the patch is applied and committed.
- [post-commit]() - Called after the actual commit is made. Because of this, it cannot disrupt the commit.
- [post-checkout]() - Run when a checkout is called after updating the worktree or after git clone.
- [post-merge]() - Called after a merge. Because of this, it cannot abort a merge.
- [update]() - This is run on the remote repo once for each ref being pushed instead of once for each push.
- [post-update]() - This is run only once after all of the refs have been pushed.

## Tools

- [Husky](https://github.com/typicode/husky) - 🐶 Git hooks made easy
- [Komondor](https://github.com/orta/Komondor) - 🐩 Git Hooks for Swift projects 
- [Quickhook](https://github.com/dirk/quickhook/) - Faster Git hook (pre-commit, etc.) runner
- [git-hooks](https://github.com/icefox/git-hooks/) - A tool to manage project, user, and global Git hooks
- [overcommit](https://github.com/brigade/overcommit/) - A fully configurable and extendable Git hook manager

## Articles

- [githooks.com](https://githooks.com)
- [Official Documentation](https://git-scm.com/docs/githooks)
- [Atlassian Git Hooks tutorial](https://ru.atlassian.com/git/tutorials/git-hooks)
- [How To Use Git Hooks To Automate Development and Deployment Tasks](https://www.digitalocean.com/community/tutorials/how-to-use-git-hooks-to-automate-development-and-deployment-tasks)
- [Automate your workflow with git hooks
](https://medium.com/backticks-tildes/how-to-automate-your-git-workflow-with-git-hooks-c905296c49bc)

## Support

If you have a question, find a bug, or just want to say hi, please open an [issue on GitHub](https://github.com/aitemr/awesome-git-hooks/issues/new). If you want to contribute, please read the [guide](https://github.com/aitemr/awesome-git-hooks/blob/master/.github/contributing.md).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Islam Temirbek](https://aitemr.github.io) has waived all copyright and related or neighboring rights to this work.