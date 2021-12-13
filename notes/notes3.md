# Desktop Environments
* GUI - Graphical User Interface
* DE - Desktop Environment
* Most common are GNOME and KDE
* Contents
  * Display Manager
  * File Manager
  * Icons (Programs)
  * Launcher
  * Menus
  * System Tray
  * Widgets
  * Window Manager

## Gnome
* Default for Ubuntu and other distros.
* GNU Network Object Model Environment
* Free Software project to develop a desktop environment and applications for it.

## KDE
* Kool Desktop environment

## The Bash Shell
* Unix shell and command language software.
* CLI - command-line interface
  * Terminal Emulator
  * Linux Console

# Managing Software
* Package - archives that contain software.

## Debian Package Management System
* DPMS to manage software on all Debian distros.
* .deb extension
* dpkg (Debian package) applications

## Advanted Package Tool
* APT - tool for managing debian packages
* sudo - requires privileges as root user
* install - install specified package
* remove - remove specified package
* ex. sudo apt install firefox flameshot caffeine -y
* ex. sudo apt purge firefox+ flameshot- caffeine- vlc+
* Search programs
  * apt search "web"
  * --help for more

## Installing .deb files
* Get the file
  * sudo dkpg -i google-chrome-stable.deb

* gdebi - simple tool to install deb files
  * sudo gdebi google-chrome-stable.deb

## Snaps and Flatpak
* Snaps - packages of apps
  * Snap Store - app store

* Flatpak - nextgen packaging software for linux.

# Linux Directory Structure
* Branch based

## Pwd Command
* Display current working directory
  * pwd

## Cd Command
* Change current working directory
  * cd + destination
    * Home Directory
      * cd
      * cd ~
      * cd $HOME
  * Previous Directory
    * cd -
  * Go Back 1 Directory
    * cd ../

## Ls command
* List content in a directory
* man ls for options
* ls
  * List hidden too
    * ls -a
  * List files inside a directory
    * ls -a ~/Pictures
  * Long List recursively
    * ls -lR ~/Pictures

## Absolute vs Relative Path
* Absolute starts are root
  * /home/user/Downloads/song.mp3
* Relative starts anywhere relative to working directory
  * pwd is /home/user
    * /Downloads/song.mp3

