# kalipanel
This repository provides a libinput gesture configuration file that emulates common Windows gestures on Linux systems. The configuration file allows users to perform touchpad or touchscreen gestures that closely resemble the gestures used in Windows.
<h1 align="center">Windows-like Gestures for libinput</h1>



<p align="center">
  <em>Emulate common Windows gestures on Linux</em>
</p>

---

## Table of Contents
- [Overview](#overview)
- [Usage](#usage)
- [Gesture Actions](#gesture-actions)
- [Contributions](#contributions)

---

## Overview

This repository provides a libinput gesture configuration file that allows users to emulate common Windows gestures on Linux systems. By using this configuration file, you can perform touchpad or touchscreen gestures that closely resemble the gestures used in Windows.

## Usage

1. Clone or download the repository.
2. Copy the `libinput-gestures.conf` file to the appropriate location on your system:
   - For system-wide configuration: `/etc/libinput-gestures.conf`
   - For user-specific configuration: `~/.config/libinput-gestures.conf`
3. If required, install the `xdotool` package on your system to enable the execution of actions.
4. Restart the libinput-gestures service or log out and log back in to apply the changes.
   'libinput-gestures-setup restart'
6. Enjoy Windows-like gestures on your Linux system!
7. alternative way of  doing is that copy the code of my conf file and paste in your system and restart the system. enjoy


## Gesture Actions

The following gestures and their corresponding actions are included in the configuration file:

- **Tap-to-click**: Perform a tap gesture to simulate a left-click.
- **Right-click**: Perform a three-finger swipe down to simulate a right-click.
- **Scroll**: Perform a three-finger swipe left or right to scroll horizontally, or swipe up or down to scroll vertically.
- **Switch applications (Alt + Tab)**: Perform a four-finger swipe left or right to switch between open applications.
- **Show desktop**: Perform a two-finger pinch-out gesture to show the desktop.
- **Zoom in and out**: Perform a two-finger pinch-in or pinch-out gesture to zoom in or out.
- **Switch virtual desktops**: Perform a four-finger swipe left or right to switch between virtual desktops.
- **Close current window**: Perform a four-finger pinch-in gesture to close the current window.
- **Go back/forward in web browsers**: Perform a two-finger swipe left or right to navigate back or forward in web browsers.

Please note that some actions may require additional software or configuration on your system. Adjust the configuration file as needed to match your preferred keybindings or applications.

## Contributions

Contributions to improve or expand the gesture mappings are welcome! If you have any suggestions or enhancements, feel free to create a pull request or open an issue.

---

<p align="center">
  Made with :heart: Perman
</p>
