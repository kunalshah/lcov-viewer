# LCOV Viewer

A simple, browser-based tool for viewing code coverage reports in a
human-friendly format.

## TLDR

View online LCOV code coverage viewer at
[kunalshah.github.io/lcov-viewer](https://kunalshah.github.io/lcov-viewer/)

## What is this?

Tools like [Bun](https://bun.com/docs/test/code-coverage) and
[Flutter](https://docs.flutter.dev/testing/overview) generate code coverage
reports in LCOV format, which is great for machines but difficult for humans to
read.

This viewer transforms the LCOV code coverage report into an easy-to-navigate,
intuitive visual interface.

With this HTML viewer, LCOV report can be viewed in a `Tree View`, or a
`List view`.

- In the **`Tree View`**, report is organized in a tree format to easily see
  code coverage by folder(s).

- In the **`List View`**, you can sort code coverage by `Name`, by
  `High to Low Coverage`, by `Low to High Coverage`, and by `Total Lines`

## How to use it

### Online (easiest)

Visit
**[kunalshah.github.io/lcov-viewer](https://kunalshah.github.io/lcov-viewer/)**
and upload your LCOV file directly in your browser.

No installation or setup required!

Your code coverage report stays completely in your browser.

### Offline

Download
[index.html](https://raw.githubusercontent.com/kunalshah/lcov-viewer/refs/heads/main/index.html)
or clone this [repository](git@github.com:kunalshah/lcov-viewer.git) and open
`index.html` in your browser or serve through a static file server like nginx.

The entire viewer is contained in a single HTML file, so it works completely
offline.

## Features

- ✨ **No dependencies** – Everything runs in your browser
- 🔒 **Privacy-friendly** – Your coverage data never leaves your machine
- 📦 **Self-contained** – Just one HTML file
- 🎨 **Clean interface** – Easy to navigate and understand your coverage

## License

This project is free to use for any purpose. No attribution required. Enjoy!
