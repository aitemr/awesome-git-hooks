## pre push 

Called prior to a push to a remote. In addition to the parameters, additional information, separated by a space is passed in through stdin in the form of "<local ref> <local sha1> <remote ref> <remote sha1>". Parsing the input can get you additional information that you can use to check. For instance, if the local sha1 is 40 zeros long, the push is a delete and if the remote sha1 is 40 zeros, it is a new branch. This can be used to do many comparisons of the pushed ref to what is currently there. A non-zero exit status aborts the push.

## invoked by 

```bash
git push
```

## pre push git hooks for:

* [SwiftLint](https://github.com/aitemr/awesome-git-hooks/blob/master/pre-push/pre-push-protect-branches) - Git pre-push hook to prevent force pushing master branch

## support

If you have a question, find a bug, or just want to say hi, please open an [issue on GitHub](https://github.com/aitemr/awesome-git-hooks/issues/new) 

## license

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Islam Temirbek](https://aitemr.github.io) has waived all copyright and related or neighboring rights to this work.