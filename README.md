# 42-get_next_line

![get_next_linem](https://user-images.githubusercontent.com/81260589/182126144-78e9af3b-0219-4e79-bdcd-c4b02a9d5937.png)

## Table of contents

- [Introduction](#Introduction)
- [How to run](#How-to-run)
- [What it does?](#What-it-does?)
- [What I've learned ?](#What-I've-learned?)

## Introduction

This project is an introduction to Input/Output system calls.

## How to run

- Clone the repository:
`git clone https://github.com/victor-ln/42-get_next_line.git`
- Access the cloned folder:
`cd 42-get_next_line`
- Add `#include "get_next_line.h` in your source code or header file.
- Compile with: ``gcc get_next_line.c get_next_line_utils.c get_next_line.h main.c``

## What it does ?

`char *get_next_line(int fd)` is a function that reads the number defined in `BUFFER_SIZE` of bytes from an opened file and returns as its name suggests, a line from it, i.e. from where the file position indicator started/stopped until a newline character.
If reaches EOF, an error occurs or an invalid file descriptor is passed, it returns NULL.

## What I've learned ?

- Implementing Static and Structures variables
- Read and Open files
- File descriptors (fd)
