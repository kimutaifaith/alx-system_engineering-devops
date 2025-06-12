# Bash Scripts Project

This project contains Bash scripts written using only `vi`, `vim`, or `emacs`, following strict rules such as:
- Each script is exactly **two lines** long.
- Only tested on **Ubuntu 20.04 LTS**.
- No use of `&&`, `||`, `;`, `bc`, `sed`, or `awk`.
- All scripts must start with `#!/bin/bash`.
- All files are executable and end with a newline.
- The project includes a `README.md` to describe each script.

---

## Scripts Description

### `0-alias`

Creates an alias named `ls` that deletes all files in the current directory.

```bash
alias ls='rm *'
