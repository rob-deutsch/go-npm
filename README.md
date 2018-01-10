## Go NPM (Private)

### Description

This is exactly the same as go-npm ([npm](https://www.npmjs.com/package/go-npm)/[github](https://github.com/sanathkr/go-npm)) except it will append the environment variable $GITHUB\_TOKEN to every HTTP(S) requests that it sends to Github.com.


### Motivation
Because goreleaser can upload releases to private Github repos using the $GITHUB\_TOKEN, and this allows go-npm to fetch those releases.
