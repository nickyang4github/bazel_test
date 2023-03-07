# bazel

This project is used to test the bazel build system.

## Setup

### Install bazel

```bash
brew install bazel
```

### Build

```bash
bazel run //:bazel_test -- update-repos -from_file=go.mod
```