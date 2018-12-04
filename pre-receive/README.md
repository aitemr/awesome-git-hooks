## pre receive 

This is called on the remote repo just before updating the pushed refs. A non-zero status will abort the process. Although it receives no parameters, it is passed a string through stdin in the form of "<old-value> <new-value> <ref-name>" for each ref.

## invoked by 

```bash
git-receive-pack
# on the remote repo
```

## pre receive git hooks for:

* [Push Ban](https://github.com/aitemr/awesome-git-hooks/blob/master/pre-receive/pre-receive-ban-on-push-to-brancht) - Git Hook for ban on push to master branch

## support

If you have a question, find a bug, or just want to say hi, please open an [issue on GitHub](https://github.com/aitemr/awesome-git-hooks/issues/new) 

## license

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Islam Temirbek](https://aitemr.github.io) has waived all copyright and related or neighboring rights to this work.