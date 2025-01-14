# ZMK config files for an Aurora Lily58


![Picture of Aurora Lily58 with nonfunctional trackpoint on right](/img/currentsetup.jpg)

See Cirque-dongle or Curque branch for Cirque Touchpad config. (not updated to current zmk branch)

## Prospector Dongle
Added support to use the Prospector Dongle ![Prospector Dongle](/img/dongle.jpg)

https://github.com/carrefinho/prospector

- Would like to see update for device connected status (usb/bt1/bt2/etc) and things like num lock/caps. Will make a fork and try when I have time.

## Trackpoint
Currently non functional (see failed workflows lol) but working on setting up trackpoint to work on right side so need to figure out new zmk listeners with trackpoint module

## Zmk Studio
Plan to impletement zmk studio once I have the trackpoint working. Need to pull in splitkb_aurora updates from zmk main. Currently using the format before zmk studio that is not compatible

## Base Setup
Keymap is based on knucklehead adapted and customized for lily58 layout.

Base Keymap can be found here by minusfive: https://github.com/minusfive/zmk-config

## Keymap

![Keymap](/img/splitkb_aurora_lily58.svg)

