# LCOV Viewer

A browser-based intuitive UI for viewing LCOV code coverage reports. UI is
mobile friendly but view it on Desktop for the best experience.

## TLDR

See online LCOV viewer at
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
  report by folder(s).

- In the **`List View`**, you can sort by:
  - `File Name`
  - `Coverage` (Amount of Code Coverage in a File)
  - `Lines` (Number of Lines in a File)
  - `Functions` (Number of Functions in a File)

## How to use it

### Online (easiest)

Visit
**[kunalshah.github.io/lcov-viewer](https://kunalshah.github.io/lcov-viewer/)**
and upload your LCOV file directly in your browser.

No installation or setup required!

Your code coverage report stays completely in your browser.

### Offline

Directly download
[index.html](https://raw.githubusercontent.com/kunalshah/lcov-viewer/refs/heads/main/index.html)
or clone this repository and open `index.html` in your browser, or serve through
a static file server like nginx.

## Features

- 🎨 **Clean interface** – Easy to navigate and understand your coverage
- 📦 **Self-contained** – Single HTML file without any dependencies
- 🔒 **Privacy-friendly**
  - Your coverage data never leaves your machine
  - No cookies
  - No tracking
  - No request to any website
  - Works offline

## License

This project is free to use for any purpose. No attribution required.
