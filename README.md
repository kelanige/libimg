# libimg

A library written in C++ against the C++17 standard for reading and writing image data.
This is a project to make image files easier to work with in C++, since at the time of writing I only know of libjpeg and libjepg-turbo, which are both C libraries.
My hope with this library is to make handling image files less painful in C++ codebases.

## Supported Filetypes

- [ ] (in progress) JPG/JPEG
- [ ] PNG

## Build

To build binaries of this library, run `bazel build //...` which will build all targets.

## Use

The easiest and currently only supported way of using this library is to add this repository to your Bazel workspace and the specific image filetype as a dependency.

## Testing

This library uses Google Test for unit testing.

## Commit Messages

For commit messages, use the format outlined in [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

