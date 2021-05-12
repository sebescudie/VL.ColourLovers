# VL.ColourLovers

[![Nuget](https://img.shields.io/nuget/vpre/VL.ColourLovers?style=flat-square)](https://www.nuget.org/packages/VL.ColourLovers)

_A small utility node that allows to search for color palettes on ColourLovers by keyword or by color and easily use them in your patch._

## Known issue
As of today (5/12/21), it seems the plugin has troubles communicating with the ColourLovers API (see [this post](https://discourse.vvvv.org/t/vl-colourlovers/19483/3) on the vvvv forum). I'm waiting for feedback from ColourLovers and will update this README when it's fixed.

## Installation

Go to gamma's command line and type

```
nuget install VL.ColourLovers -pre
```

For more information on how to install nugets, visit the [Gray Book](https://thegraybook.vvvv.org/reference/libraries/referencing.html).

## Usage

Press <kbd>F1</kbd> to open the help browser and look for `ColourLovers`. There's a help patch that shows how to use the node.

## Features

- Search for palettes by keyword or by color
- Either specify the color yourself, or use the built-in color picker that lets you pick any color from your screen with a simple double-click
- Mark palettes as favorites and save them to disk for later use

## Credits

Uses the [ColourLovers](https://github.com/scottt732/ColourLoversDotNet) nuget by scottt732
