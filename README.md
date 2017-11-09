# [api2go] with [gin] example

[![Build Status](https://travis-ci.org/LewisWatson/api2go-with-gin-example.svg?branch=master)](https://travis-ci.org/LewisWatson/api2go-with-gin-example)

This application, written in [go], demonstrates using [api2go] with the [gin].

## Build

`go get` dependencies

```bash
go get -tags=gingonic github.com/manyminds/api2go
```

With the dependencies downloaded, we can build the application:

```bash
go build -tags=gingonic
```

### Run

Run the static binary:

```bash
./api2go-with-gin-example
```

[go]: https://golang.org/ "The Go Programming Language"
[api2go]: https://github.com/manyminds/api2go "JSONAPI.org Implementation for Go"
[gin]: https://github.com/gin-gonic/gin "HTTP web framework written in Go"
[dep]: https://github.com/golang/dep "Go dependency management tool"