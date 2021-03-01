# p1DongjinKang
# Project 1: The microwave interface

## Microwave

<img src="https://github.com/Dongjin-Kang/p1DongjinKang/issues/1#issue-818364294" width="50%" height="50%">

The purpose of Proclipsing is to lower the difficulty of using Processing in Eclipse.

This Eclipse plugin bootstraps the creation of an Eclipse Java project that relies on the Processing **.jar** dependencies. This is different from the [processing-eclipse](http://github.com/processing/processing-eclipse) experiment, which adheres to the PDE / codegen approach found in the Processing IDE itself.

It allows you to easily create a Processing project in Eclipse by simply putting in the path to your Processing app, the path to your Sketch folder (for contributed libraries), and then selecting the libraries you want. Proclipsing then creates a project with the desired libs (with native libraries), skeleton package structure, and a PApplet.

You can also add or remove libraries later with an option in the project preferences menu.

## Installing

1. Download a [release](https://github.com/ybakos/proclipsing/releases) **.zip** file.
2. Unzip the file and place the folder in a convenient location.
3. In Eclipse, select the menu item _Help > Install New Software_. In the dialogue that appears, select the _Add..._ button. Enter **Proclipsing** as the _Name:_, and select the _Local..._ button. Navigate to the location of your Proclipsing folder, and within, select the **proclipsingSite** folder and select the _Open_ button.
4. Back in the _Install_ dialogue, select the _Select All_ button, and then select _Next >_.
5. Accept the license agreement and select _Finish_. If you are prompted to restart Eclipse, do it.

Here's an old [Proclipsing Setup Screencast](https://vimeo.com/19076476).

## P5 Exporter

We've also teamed up with Daniel Howe, so you can get his P5 Exporter from the same update site. With P5 Exporter, you can export projects from eclipse similar to the way you do from the Processing IDE.
