# Linux Basics - DevOps Learning

A hands-on learning repository documenting my journey into Linux and DevOps fundamentals through practical command-line exercises.

## Overview

This project covers essential Linux commands for file management, file inspection, searching, compression, downloading files, permissions, and environment variables.

The exercises were performed in Ubuntu using Windows Subsystem for Linux (WSL).

## Topics Covered

| Topic | Commands / Concepts |
|---|---|
| Directory and file management | `mkdir`, `touch`, `cd`, `pwd`, `ls`, `mv` |
| Viewing file contents | `cat`, `head`, `tail` |
| Searching text | `grep` |
| Compression and extraction | `zip`, `unzip` |
| Downloading files | `wget` |
| File permissions | `chmod`, Linux permission values |
| Environment variables | `export`, `echo` |

## Getting Started

### Prerequisites

- Windows with WSL enabled
- Ubuntu Linux
- Internet connection for downloading files
- ZIP utilities (`zip` and `unzip`)

### Example Exercises

Display the first five lines of a system file:

```bash
head -n 5 /etc/passwd
```

Search for lines containing `root`:

```bash
grep "root" /etc/passwd
```

Create a ZIP archive:

```bash
zip -r test_dir.zip test_dir
```

Set read-only permissions for everyone:

```bash
chmod 444 secure.txt
```

Set and display an environment variable:

```bash
export MY_VAR="Hello, Linux!"
echo "$MY_VAR"
```

## Learning Outcomes

- Practised navigating Linux directories and managing files.
- Learned to inspect files and search for text using command-line utilities.
- Practised creating and extracting ZIP archives.
- Understood basic Linux permissions and environment variables.

## Repository Structure

```text
devops-learning/
├── README.md
├── linux-basics/
│   ├── test_dir/
│   ├── test_dir.zip
│   ├── unzipped_dir/
│   ├── secure.txt
│   └── rfc9110.txt
└── screenshots/
```

*The structure above is the intended organization; update it to match the files actually committed to this repository.*

## Author

Aditi Ghule

This repository is part of my ongoing hands-on learning in Linux and DevOps fundamentals.
