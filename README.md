# GNOME Screenshot Uploader

GNOME Screenshot Uploader is a simple wrapper around GNOME Screenshot which
enables you to automatically upload a given screenshot to your webserver and
have the URL to it directly placed in your clipboard. It also gives you a nice
upload progressbar in the lower left corner of your screen.

## Requirements

You need GNOME Screenshot version 3.5.2 or higher to use this application.

## Installation

Copy the .gnome-screenshot-uploader.cfg file to your home directory and adjust
the values. Then install an upload handler script like this one on your server:

https://github.com/EvanDotPro/GtkGrab/blob/master/handler.php

## Usage

You can now call gnome-screenshot-uploader and it will automatically upload
any taken screenshot. For convenience, assign keyboard shortcuts to call it
with specific parameters.

