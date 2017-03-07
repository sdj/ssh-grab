# Grab Remote Agent

Import SSH environment variables from the oldest child of the newest sshd process owned by the user.

This allows picking up the AGENT settings from an ssh session in a non-child shell.

Example: Access agent from a Windows 10 Pageant PuTTY login within a Linux graphical Desktop Terminal shell.

# Usage

Script must be sourced in the shell, so the following at your bash prompt, or added to .bashrc:

   . grab-remote-agent
