# Awesome Git Hooks [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [Git hooks](https://git-scm.com/docs/githooks)

## Contents
- [About](#about)
- [Useful Git Hooks scripts](#useful-git-hooks-scripts)
- [Tools](#tools)
- [Articles](#articles)
- [Video Tutorials](#video-tutorials)
- [Support](#support)

## About 

Git Hooks are scripts that run automatically every time a particular event occurs in a Git repository.

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

## Tools

- [Husky](https://github.com/typicode/husky) - Git hooks made easy.
- [Komondor](https://github.com/orta/Komondor) - Git Hooks for Swift projects.
- [Quickhook](https://github.com/dirk/quickhook/) - Faster Git hook (pre-commit, etc.) runner.
- [git-hooks](https://github.com/icefox/git-hooks/) - A tool to manage project, user, and global Git hooks.
- [overcommit](https://github.com/brigade/overcommit/) - A fully configurable and extendable Git hook manager.

## Articles

- [githooks.com](https://githooks.com)
- [Official Documentation](https://git-scm.com/docs/githooks)
- [Atlassian Git Hooks tutorial](https://ru.atlassian.com/git/tutorials/git-hooks)
- [How To Use Git Hooks To Automate Development and Deployment Tasks](https://www.digitalocean.com/community/tutorials/how-to-use-git-hooks-to-automate-development-and-deployment-tasks)
- [Automate your workflow with git hooks
](https://medium.com/backticks-tildes/how-to-automate-your-git-workflow-with-git-hooks-c905296c49bc)
- []()

## Video Tutorials 

- [Introduction to Git Hooks](https://www.youtube.com/watch?v=8-JL6NOTZOw)
- [Git hooks, practical uses (yes, even on Windows)](https://www.youtube.com/watch?v=fMYv6-SZsSo)
- [Life’s better with Git hooks](https://www.youtube.com/watch?v=RG26-Iozg70)
- [Husky and the Git Hooks](https://www.youtube.com/watch?v=EpxkBgd8yq8)

## Support

If you have a question, find a bug, or just want to say hi, please open an [issue on GitHub](https://github.com/aitemr/awesome-git-hooks/issues/new). If you want to contribute, please read the [guide](./contributing.md).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Islam Temirbek](https://aitemr.github.io) has waived all copyright and related or neighboring rights to this work.
