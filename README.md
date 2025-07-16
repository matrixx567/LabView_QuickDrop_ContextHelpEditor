# LabView QuickDrop ContextHelpEditor

[![Image](https://www.vipm.io/package/mnprojects_lib_quickdrop_contexthelpeditor/badge.svg?metric=installs)](https://www.vipm.io/package/mnprojects_lib_quickdrop_contexthelpeditor/) [![Image](https://www.vipm.io/package/mnprojects_lib_quickdrop_contexthelpeditor/badge.svg?metric=stars)](https://www.vipm.io/package/mnprojects_lib_quickdrop_contexthelpeditor/)

A QuickDrop plugin that opens an editor for easier VI documentation.


It simply allows writing documentations for VIs and Typedefs during the development process. The editor provides an intuitive navigation only using the keyboard for fast writing.


![Screenshot](../master/docs/Screenshot.png)

## Installation

The plug-in is published as a VIPM Community package. Search for `QuickDrop ContextHelpEditor` in the VI Package Manager and install it easily. Otherwise you can download the VIP package from the Release page and install it manually.

## Usage

The Quick Drop plug-in uses the default shortcut `H`.

Firstly press `CTRL+SPACE` to open the quick drop dialog, then press `CTRL+H` to open the plug-in dialog 

During the usage the documentation entries will only be modified but the VI will not be saved. It is also possible to undo your work using `CTRL+Z`.

## Examples

### Documentation of a VI and its connector pane

![VI](../master/docs/VI.png)


### Documentation of a Typedef

![Typedef](../master/docs/Typedef.png)



## License

This project is released under the terms of the MIT license, a copy of which can be found in LICENSE.

## Hints

The plug-in is developed with LabVIEW 2020.
