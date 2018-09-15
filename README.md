## The homebrew tap for anyenv

[![Build Status](https://travis-ci.org/tya/homebrew-anyenv.svg?branch=master)](https://travis-ci.org/tya/homebrew-anyenv)

### Usage

```
$ brew tap tya/anyenv
```

And then install anyenv:

```
$ brew install anyenv --HEAD
```

```
$ anyenv install scalaenv
# You need to run `anyenv init` again to make `*env` available in your PATH
$ eval "$(anyenv init -)"
```
