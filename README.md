Collapser
===

[![GoDoc](https://godoc.org/github.com/TypeTwo/go-collapser?status.svg)](https://godoc.org/github.com/TypeTwo/go-collapser)
[![Build Status](https://travis-ci.org/TypeTwo/go-collapser.svg?branch=master)](https://travis-ci.org/TypeTwo/go-collapser)
[![Go Report Card](https://goreportcard.com/badge/github.com/TypeTwo/go-collapser)](https://goreportcard.com/report/github.com/TypeTwo/go-collapser)

Package `go-collapser` implements a function call deduplication utility.

---

## Install

```sh
go get github.com/TypeTwo/go-collapser
```

## Design goals

- **No external dependencies** - only stdlib packages 
- **Easy to use** - simple, tested and documented API
- **Small code base** - do one thing and do it well
- **Composable** - easy to plug into different contexts (http handlers, db access, remote apis, ...)

## License

The Collapser source files are distributed under the BSD-style license found in the [LICENSE](https://github.com/TypeTwo/go-collapser/blob/master/LICENSE) file.
