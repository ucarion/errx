# errx

**errx** is a set of utilities for richer errors in Golang. The priorities in
designing this package are:

* **Idiomatic Golang.** This package does not try to go against the grain. There
  are existing patterns for errors in Golang, and this package does not fight
  them.
* **Testability.** Go's philosophy of errors-as-data makes testing error
  conditions very easy. This package attempts to make it easy to test errors, be
  they internal or returned from your library.
* **Composition.** Oftentimes, you want to enhance errors with metadata, be they
  for logging extra context or for producing telemetry information. `errx` helps
  you do so, without interfering with your ability to do conditional logic based
  on what errors you've encountered. `errx` supports joining errors together, or
  adding a "cause" to an error.
* **Compatibility.** `errx` can be used as little or as much as you desire
  within your codebase. It plays just fine with errors from other packages, and
  other packages can use `errx` errors without any issues.

## Documentation

For detailed documentation, see GoDoc:

https://godoc.org/github.com/ucarion/errx

## Usage

## Design
