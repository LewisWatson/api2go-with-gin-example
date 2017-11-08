# [api2go] with [gin] example

This application, written in [go], demonstrates using [api2go] with the [gin].

## Build

Dependencies are managed by the [dep] tool. To download dependencies to a `vendor` directory

```bash
dep ensure
```

With the dependencies downloaded, we can build the application:

```bash
go build
```

### Run

Run the static binary:

```bash
./crud_example
```

[go]: https://golang.org/ "The Go Programming Language"
[api2go]: https://github.com/manyminds/api2go "JSONAPI.org Implementation for Go"
[gin]: https://github.com/gin-gonic/gin "HTTP web framework written in Go"
[dep]: https://github.com/golang/dep "Go dependency management tool"