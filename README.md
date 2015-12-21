# cl-gems-server

# setup
## install roswell
[roswell's wiki](https://github.com/snmsts/roswell/wiki/1.-Installation)

## install qlgit
```
$ gem install qlgit
$ export QUICKLISP=$(ros run --eval '(progn (princ ql:*quicklisp-home*) (exit))')
```

## install http-ink
```
$ qlgit install mocchit/toy-gun
$ qlgit install mocchit/http-ink
```