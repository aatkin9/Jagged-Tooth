# Jagged-Tooth

## Requirements
----
* A linux operating system with bash installed.

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
    * -d: Print the home directory.
    * -h: Print the help information.
* holidays
  * holidays (options) [dateString] (holidayName, if -c or -d)
  * Show a list of holidays from a local list and www.checkiday.com for a date
  * Insert and delete local holidays using the appropriate commands.
  * Options...
    * -a: Show both online and local holidays
    * -c: Create a local holiday
    * -d: Delete a local holiday
    * -h: Print the help information
    * -l: Show only local holidays
    * -o: Show only online holidays
* whoowns
  * whoowns [directory]
  * Determine the owner of a file or directory.
  * Options...
    * -h: Print the help information.
