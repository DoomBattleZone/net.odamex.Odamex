# Odamex Flatpak

## Description

This is the unofficial flatpak for Odamex - Online Multiplayer Doom port with a strong focus on the original gameplay while providing a breadth of enhancements. You can find more information at Odamex' official repository located [here](https://github.com/odamex/odamex) or by visiting the official [website](https://odamex.net/).

## Installation

To install this flatpak you have to do the following:

* Make sure you have `flatpak` package installed on your system. To install it, visit [this](https://flatpak.org/setup/) page and choose your distribution.
* By using flatpak, install Freedesktop runtime: `flatpak --user install flathub org.freedesktop.Platform//21.08 org.freedesktop.Sdk//21.08`
* Install `flatpak-builder` package to build flatpak packages.
* Build and install this flatpak by executing the following command in the terminal: `flatpak-builder --user --install --force-clean build-dir net.odamex.Odamex.yaml`. Wait for it to finish.
* Run installed flatpak by executing `flatpak run net.odamex.Odamex` or by clicking on `Odamex` desktop entry located under `Games` category in your distribution's app menu.

## Notes

* Music may or may not work on some distributions. Reason unknown.
* `ODAMEX.WAD` is not included by default in this bundle.
* This flatpak is currently not available as a downloadable package in any of the repositories (such as Flathub) due to its experimental nature. Expect issues and inconsistency. You've been warned.
