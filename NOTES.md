# POST INSTALL NOTES:
## ubuntu-desktop:
amdgpu-pro needs to be installed for HDMI sound output to work.
Specifically: Version 17.10 is required, 16.40 will crash your login screen.
http://support.amd.com/en-us/kb-articles/Pages/AMDGPU-PRO-Install.aspx

# Additions:
## Redshift fix
geoclue2 - enable location services in gsettings

## Automatically sort out terminator
set terminator as default terminal.
$ sudo update-alternatives --config x-terminal-emulator

## Automatically add dotfiles .vimrc zsh themes, terminator theme etc...

