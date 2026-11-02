# Markdown to HTML compiler

![](https://github.com/kseniia1803/markdown-compiler-solutionish/workflows/doctests/badge.svg)&nbsp;
![](https://github.com/kseniia1803/markdown-compiler-solutionish/workflows/flake8/badge.svg)&nbsp;
![](https://github.com/kseniia1803/markdown-compiler-solutionish/workflows/command_line/badge.svg)&nbsp;

A simple project for converting markdown files to HTML.

Basic usage:
```
$ markdown-compiler example/README.md
```

<img src='examples/example.png' width=300px>

Fancy CSS formatting can be included with the flag `--add_css`:
```
$ markdown-compiler example/README.md --add_css
```

<img src='examples/example-css.png' width=300px>
