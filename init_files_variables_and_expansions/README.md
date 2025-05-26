# init_files_variables_and_expansions

## 0-alias

This script creates an alias named `ls` that runs `rm *`.  
When you source the script (`source ./0-alias`), typing `ls` will remove all files in the current directory.  
Using `\ls` will run the original `ls` command, bypassing the alias.

The script is exactly two lines long and starts with the `#!/bin/bash` shebang.

**Warning:** Be careful when using this alias as it will delete files!
