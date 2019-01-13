## post-receive 

This is run on the remote when pushing after the all refs have been updated. It does not take parameters, but receives info through stdin in the form of "<old-value> <new-value> <ref-name>". Because it is called after the updates, it cannot abort the process.

## invoked by 

```bash
git-receive-pack 
# on the remote repo
```

## post-receive git hooks for:

* [post-receive-specific-folder](https://github.com/aitemr/awesome-git-hooks/blob/master/post-receive/post-receive-specific-folder) - hook to deploy the code being pushed to production branch to a specific folder

## support

If you have a question, find a bug, or just want to say hi, please open an [issue on GitHub](https://github.com/aitemr/awesome-git-hooks/issues/new) 

## license

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Islam Temirbek](https://aitemr.github.io) has waived all copyright and related or neighboring rights to this work.