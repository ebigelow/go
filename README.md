# Go2Skicka

Basic go stuff to get skicka up and running. This lets you use google drive from the command line, e.g. `skicka download my/big/file.zip ./file.zip`

Throw this in your .bashrc:

```
# Go
export GOROOT=$HOME/lib/go
export GOPATH=$HOME/lib/go/code
export PATH=$PATH:$HOME/lib/go/bin:$GOPATH/bin
```

and then run `skicka init` to log into your google drive account. After that everything should work!
