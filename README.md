# libjpeg-cpp

A JPEG library written in C++ against the C++20 standard. This is a project to make JPEG files easier to work with in C++, since at the time of writing I only know of libjpeg and libjepg-turbo, which are both C libraries. My hope with this library is to make handling JPEG files less painful in C++ codebases.

## Build

To build binaries of this library, run `bazel build //...` which will build all targets.

## Testing

This library uses Google Test for unit testing.

## Commit Messages

For commit messages, use the format outlined in (Conventional Commits)[https://www.conventionalcommits.org/en/v1.0.0/].

