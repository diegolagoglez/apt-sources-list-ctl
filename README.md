# APT Sources List File Manager

## Introduction

This utility manages APT Sources List files (usually `/etc/apt/sources.list` and `/etc/apt/sources.list.d/*.list`) to verify, add and remove lines, remove duplicates and more.

> NOTE: This utility is under developent.

## Usage:

```bash
usage: apt-sources-list-ctl [-h] [-f FILE] [-q] [-p]
                            [--action {check,remove-duplicates}] [--version]

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  Set the file to parse (default:
                        /etc/apt/sources.list).
  -q, --quiet           Do not print the parsed file after applying all the
                        actions.
  -p, --print           Print the parsed file after applying all the actions.
  --action {check,remove-duplicates}
                        Specify actions to do on lines. Can be specified
                        multiple times.
  --version             Show the program version and exits.
```

## License

GPLv3

[Diego Lago](diego.lago.gonzalez@gmail.com)

