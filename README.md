# Screen lock

A simple screen lock that uses i3lock.
The script takes a screenshots and pixelizes it before using it as background.
The user must enter his password to unlock the screen.

![locked screen](screen.png "locked screen")

## Requirements

- scrot

  Can be installed with a package manager e.g. `apt install scrot`.

- convert (from [ImageMagick](https://imagemagick.org/))

  Can be installed with a package manager e.g. `apt install imagemagick`.

- [i3lock](https://github.com/i3/i3lock)

  Can be installed with a package manager e.g. `apt install i3lock`.

## Installation

Clone the repository wherever you want and create a symlink  in a location that
belongs to your PATH. For example, a local installation would look like this.

```
git clone --depth 1 https://github.com/Leo843/lock.git ~/.opt/lock
ln -s ~/.opt/lock/lock ~/.local/bin/lock
```

## Usage

The session is locked when the script is exectued.
The session can be unlocked by entering the password of the user.

```
lock # lock the session
```
