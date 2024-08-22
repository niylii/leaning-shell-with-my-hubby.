In this chapter, we'll learn about permissions, which are essentially the access rights that a user or program can have to a specific file or directory. These permissions have three types:

* **Read (r):** Allows you to view the contents of a file or directory.
* **Write (w):** Allows you to modify or create files within a directory.
* **Execute (x):** Allows you to run a file (usually a program or script).

These permissions can also be represented as a single digit:

* **4:** Read permission
* **2:** Write permission
* **1:** Execute permission
* **0:** No permission

These digits can be combined by addition.

We also have different entities that receive permissions:

* **Owner:** The person who created the file or directory.
* **Group:** A group of users who share access rights.
* **Others:** Everyone else on the system.

Each of these entities can have any combination of the three permissions.

**Commands for Managing Permissions of a File:**

* **`chmod`:** Changes the permissions of a file or directory.
    * **Syntax:** `chmod [options] [mode] [filename]`

* **`chown`:** Changes the owner (can also change the group).
    * **Syntax:** `chown [options] [new_owner] [filename]` or `chown [options] [new_owner:new_group] [filename]`

* **`chgrp`:** Changes the group of a file.
    * **Syntax:** `chgrp [options] [new_group] [filename]`

* **`su`:** Switches to another user, including the root user.

* **`sudo`:** Allows a normal user to execute a single command with root privileges (user ID is not changed).

**Commands for Creation and Printing:**

* **`useradd`:** Creates a user.
    * **Syntax:** `useradd [options] username`

* **`groupadd`:** Creates a group.
    * **Syntax:** `groupadd [options] groupname`

* **`id`:** Prints real and effective user and group IDs.
    * **Syntax:** `id [username]`

* **`groups`:** Prints the groups a user is in.
    * **Syntax:** `groups [username]`

* **`whoami`:** Displays the current user.

That's all for this chapter, thank youu.
