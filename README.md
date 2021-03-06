# ImageFiller for Sketch

This plugin makes it easy to automatically fill layers in Sketch with your own images. On each run, it will randomly fetch images from a folder you've populated and apply them to the layers in your current selection.

![example](http://cl.ly/image/0q200I0y081y/example.png)

*Don't want to use custom images? Try the pre-filled [Content Generator](https://github.com/timuric/Content-generator-sketch-plugin), instead. It comes with dummy data for avatars, names, places and more.*

## ImageFiller's features

* Apply images to hundreds of layers in a single click
* Designed to be modified! Use your own images from anywhere on your computer (eg. shared dropbox folder)
* Traversing! Images in subdirectories are also included!
* Works great with both shapes and bitmap layers
* Never picks the same photo twice (unless there are no more available in the folder)
* Use your own custom menu structure in Sketch by placing the .sketchplugin files in nested subdirectories

## Installation
1. Open Sketch and choose Plugins > Reveal Plugins Folder
1. [Download this project](https://github.com/awt2542/ImageFiller/archive/master.zip) and place the folder inside the Plugins directory.
1. Rename it to something prettier than "ImageFiller-master" (this will be the name of the menu item in Sketch)
1. Select some layers in Sketch and run the plugin from the Plugins menu.

## How to add your own image catalogue
1. Duplicate one of the existing .sketchplugin files and change the image path to a folder on your computer
1. Open Sketch, select a few layers and run the plugin from the Plugins menu

## How to remove the example images
1. Delete the .sketchplugin file
1. Delete the corresponding folder under /Photos.

## Contact
Twitter: [@andreaswah](http://twitter.com/andreaswah)
