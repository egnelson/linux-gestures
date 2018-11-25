# linux-gestures
Gestures for Linux using libinput-gestures.

## Requirements

- Python 3.6

- [libinput-gestures](https://github.com/bulletmark/libinput-gestures)

## Installation
libinput-gestures.conf goes in your $HOME/.config directory.

winmgr goes somewhere in your PATH.

## Running
Add the 'libinput-gestures' executable to your desktop environment's startup applications. It should pick up your config automatically.

## winmgr
winmgr takes a command- either 'up', 'down', 'fullscreen', 'move' or 'switch'- and an optional direction- 'left' or 'right'.

'move' will move the focused window one desktop in the provided direction.

'switch' will switch one desktop in the indicated direction.

'up' maximizes an unmaximized window, or fullscreens a maximized window.

'down' unfullscreens a fullscreen window (to its previous state, either maximized or unmaximized), unmaximizes a maximized window, or minimizes an unmaximized window.

'fullscreen' fullscreens a window.

## libinput-gestures.conf
It is currently set up so that a three-finger swipe left switches the desktop to the right (and vice versa), a four-finger swipe to the left moves the active window one desktop to the left (and vice versa).

The two-finger zoom gesture fullscreens the active window.

If you're running elementary OS, a down four-finger swipe opens Multitasking View (expose).

## Things that are unsupported
* Workspace layouts that aren't a single row.

