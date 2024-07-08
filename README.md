# Hello World

This is a very simple example of printing "hello, world" in golang. The purpose of this project is not showing how to print "hello, world", but to perform an experiment of releasing go application binary using github actions.

## Project

I saw an [action](https://github.com/wangyoucao577/go-release-action) that help releasing go application binary for multiple OS and architecture. This repository is just a so-called POC of applying that.

## Expected output

- Go CLI application built for:
  - Linux with AMD64 architecture
  - Linux with ARM64 architecture
  - Windows with AMD64 architecture
  - Darwin with AMD64 architecture
  - Darwin with ARM64 architecture
- Application versioning by release tag name
  - Running the application should print out application version
- Application is released along with README.md
- All releases should be compressed with tar.gz or zip