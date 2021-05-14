# Useful Bash Snippets

## Relative path in bash

Scipt to get the parent dir of the script that is being called.

    parent_dir=$( cd "$(dirname "${BASH_SOURCE[0]}")" ; pwd -P )
