# golang-glide
Docker container for building go apps with glide dependencies. Has godeps as well for good measure.

Run with the following.
```docker run --rm -v ${PWD}:/go/src/app -w /go/src/app lrodham/golang-glide /bin/sh -c "glide install && go build"```
