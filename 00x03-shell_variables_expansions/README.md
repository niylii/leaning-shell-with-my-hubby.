For this chapter we'll treat various concepts and commands .

we will start witth **Shell Initialization Files** :
* **`/etc/profile`:** This file sets up system-wide environment variables and aliases.
* **`/etc/profile.d`:** This directory contains shell scripts that are sourced by `/etc/profile`. Each script in this directory sets up specific environment variables or aliases.
* **`~/.bashrc`:it is used to set up user-specific environment variables, aliases, and shell prompts.

**Variables**

we have several types for this one :
* **Local Variables:**  Variables defined within a function or script.
* **Global Variables:** Variables defined outside of functions or scripts. They are accessible from anywhere in the shell session.
* **Reserved Variables:**  Special variables that have predefined meanings in the shell.

**For creating, updating, and deleting Shell Variables:**

* **Create:** `variable_name=value`
* **Update:** `variable_name=new_value`
* **Delete:** `unset variable_name`

**Reserved Variables:**

Are those with predefined meanings and functionalities like :
* **`HOME`:**  The path to the user's home directory.
* **`PATH`:**  A colon-separated list of directories where the shell searches for executable commands.
* **`PS1`:**  The primary shell prompt string.

**Special Parameters:**

are also predefined variales in shell scripting like :
* **`$0`:**  The name of the current script or command.
* **`$1`, `$2`, ...:**  The first, second, and subsequent arguments passed to a script or command.
* **`$*`:**  All positional parameters as a single string.
* **`$@`:**  All positional parameters as separate strings.
* **`$?`:**  The exit status of the last command executed.

**Expansions**

is literally the process of replacing special characters or patterns with their actual values like :
* **Single Quotes (`'...'`):**  Prevent shell interpretation of characters within the quotes.
* **Double Quotes (`"..."`):**  Allow shell interpretation of variables and some special characters within the quotes.
* **Command Substitution (`$()` or backticks):**  Executes a command and replaces it with its output.

**Shell Arithmetic**
* **`$(( expression ))`:**  Evaluates an arithmetic expression.
* **Operators:** `+`, `-`, `*`, `/`, `%` (modulo), `**` (exponentiation)

**The `alias` Command**
is a user defined command that shell will substitute for another command or series of commands .
* **Create an alias:** `alias alias_name='command'`
* **List aliases:** `alias`
* **Temporarily disable an alias:** `unalias alias_name`

**How to Execute Commands from a File:**
* **`. filename` or `source filename`:**  Executes the commands in the specified file in the current shell environment.
**Additioal informations:**
* **`$ ls -l *.txt`:** This command lists files in the current directory that end with ".txt" in a long format.
    * `$` is the shell prompt, indicating you're ready to enter a command.
    * `ls` is the command to list directory contents.
    * `-l` is an option to list files in a long format (including permissions, owner, size, etc.).
    * `*.txt` is a wildcard pattern matching any files ending with ".txt".

  this is it for this one , thank youu .
