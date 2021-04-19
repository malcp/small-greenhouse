# Small parametric greenhouse
Small greenhouse with four shelves, three of them removable, and a window on the roof that can be built using very basic tools and sized to fit into almost any space.

The full assembly is in draws/Main.FCStd. It also contains the spreadsheet used to define the sizes.

![Greenhouse pic](/images/greenhouse.png)

## Prerequisites
- [FreeCAD][freecadweb]. Version 0.19 works, but other version could work as well.
- FreeCAD's Assembly2+ addon. v0.4.53 at the moment of writing this document. It can be installed from inside FreeCAD using the Addon Manager.

## Configuration
In order to tweak the size of the greenhouse, follow the below steps:
1. Clone the project: `git clone https://github.com/malcp/small-greenhouse.git`
2. Open the main file with FreeCAD: `draws/Main.FCStd`
3. Open the parameters spreadsheet. It is called `params`. ![Parameters pic](/images/params.png)
5. Set the desired sizes and save the document.
6. Go back to `draws/Main.FCStd` and click to `Update parts imported into the assembly` and then `Update imports recursively`.
7. Finally, update the parts lists.

## Cut lists
https://www.opticutter.com/linear-cut-list-calculator and https://www.opticutter.com/cut-list-optimizer have been used to calculate the amount of wood and plastic boards required for building the greenhouse.

## License
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
[freecadweb]: https://www.freecadweb.org/