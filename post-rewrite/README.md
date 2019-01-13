## post-rewrite 

This is called when git commands are rewriting already committed data. In addition to the parameters, it receives strings in stdin in the form of "<old-sha1> <new-sha1>".

## invoked by 

```bash
git commit --amend 
git-rebase
```

## post-rewrite git hooks for:

* [post-rewrite-move-refs](https://github.com/aitemr/awesome-git-hooks/blob/master/post-rewrite/post-rewrite-move-refs) - hook to make local refs move automatically on rewrites.
 
## support

If you have a question, find a bug, or just want to say hi, please open an [issue on GitHub](https://github.com/aitemr/awesome-git-hooks/issues/new) 

## license

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Islam Temirbek](https://aitemr.github.io) has waived all copyright and related or neighboring rights to this work.