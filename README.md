Written by: James Garijo-Garde | for: public use | on: 5/21/2018

`subl` Script for Bash on WSL, Version 1.0
==========================================


## Description:
This is a bash script that allows a user of the [Windows Subsytem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/about)
to launch [Sublime Text](https://www.sublimetext.com) from their Linux Bash
command line and pass in filename arguments for Sublime Text to handle.

## How to Use:
1. Move the `subl` file into the `/bin` directory of your Linux distribution of choice.
2. Run `chmod 755 subl` to give yourself read/write/execute permission and others read/execute permission
3. Type `subl` in the Bash command line to launch Sublime Text. Pass in arguments as desired.

## Known Issues:
* File names with spaces surrounded by quotation marks cannont be passed in as arguments.

## References:
* [LinuxCommand.org](http://linuxcommand.org/lc3_writing_shell_scripts.php)
