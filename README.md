# A shell script template suitable for most software developers

This repository contains:

* [`hello`](hello): take this script with you and modify it at leisure.
* [`hello-teacher`](hello-teacher): is a commented version of `hello`
  for learning rather than for production code.

Short advice for successful shell scripting:

1. Treat it like any other programming language.
2. Require a modern version of bash (>= 4.3).
3. Use `"$thing"`, not `$thing` unless you want to split the string.
4. Learn the [scoping rules](https://twitter.com/mjambon/status/1264718107861413889)
   and how to use functions.
5. Learn [how to use arrays](https://www.gnu.org/software/bash/manual/bash.html#Arrays).
6. Use [ShellCheck](https://shellcheck.net). It's helpful for
   learning, not just for going after production code.

Common conventions that minimize annoyances:

* Executable files should have no extension. It's `hello`, not `hello.sh`.
* Environment variables should use all-caps e.g. `"$USER"`. Ordinary shell
  variables should use lowercase e.g. `"$name"`.
