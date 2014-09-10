# Introduction

This is an implementation of a userspace driver for using the Boogie Board Sync
as a tablet under linux.  It uses pyusb to interface with the device and the
UInput system (via evdev for python) to generate input signals.  It's still
early days, so it may be unstable.

# Requirements

- python
- pyusb
- evdev
