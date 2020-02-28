# Jagged-Tooth

## Requirements
----
* A linux operating system with [bash] (https://www.gnu.org/software/bash/manual/html_node/Installing-Bash.html) installed.

## How to install
----
1. Create a directory. We are using `~/bin` for this example.

1. Add the desired executable files to `~/bin`.

1. Update your path variable to include the created directory. To keep this persistent you want to add the following command to your `.bash_profile` which can be found under your home directory:
`export PATH=$PATH":$HOME/bin"`

1. Reload `.bash_profile` by doing `. ~/.bash_profile`.

1. The scripts can now be run from anywhere by simply typing their name.

## The Commands
----
* unfo
  * unfo (options) [username]
  * Retrieve various information about a user.
  * Options...
    * -a: Print all of the information (Done by default).
    * -s: Print the status.
    * -u: Print the username.
    * -n: Print the full name.
    * -t: Print the time of last log in.
    * -h: Print the home directory.
* findsize
  * findsize [option] \(directory)
  * Find the largest/smallest file or directory.
  * Options...
    * -b: Find the biggest file or directory.
    * -s: Find the smallest file or directory.
