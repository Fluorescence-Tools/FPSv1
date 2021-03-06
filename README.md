# FPS

## Overview
The graphical user interface and libraries of the FRET Positioning 
System [Nature Methods in 2012](https://www.nature.com/articles/nmeth.2222).

FRET positioning refers to finding spatial positions and orientations 
of multiple structural subunits subject to a set of experimental FRET 
restraints. Each unit is assumed to have a known rigid structure. In 
addition to the restraints provided explicitly, clashes between subunits 
are taken into account. No other interactions (electrostatic, 
hydrophobic, ...) are considered. For comparable approaches see e.g. 
(Brunger et al, 2011) (also referred to as rigid body docking or 
rigid body MD).

FRET screening is a complementary method of "filtering" a structure 
library with respect to agreement with FRET data.

## Download

The original MS-Windows software (v1.1) can be found in the "release" 
folder.  This version was wrapped for the use on MacOS (tested in High 
Sierra 10.13.4).

## Installation

### Windows

To install/use FPS simply download and unzip the following file 
and install a corresponding VC runtime for your Windows installation.

[FPS-Windows](https://github.com/Fluorescence-Tools/FPS/releases/download/1.1/FPS-v1.1-windows.zip)

[Windows x64](https://github.com/Fluorescence-Tools/FPS/releases/download/1.1/vcredist_x64_6195.EXE)

[Windows x32](https://github.com/Fluorescence-Tools/FPS/releases/download/1.1/vcredist_x86_6195.EXE)

### MacOS
To use FPS on MacOS download and unzip the following archieve

[FPS-MacOS](https://github.com/Fluorescence-Tools/FPS/releases/download/1.1/FPS-v1.1-macos.zip)

# Citation

Additional information is available in FPS toolkit paper: [![DOI for citing FPS](https://img.shields.io/badge/DOI-10.1038%2Fnmeth.2222-blue.svg)](https://doi.org/10.1038/nmeth.2222)
> Kalinin, S., Peulen, T., Sindbert, S., Rothwell, P.J., Berger, S., Restle, T., Goody, R.S., Gohlke, H. and Seidel, C.A., 2012. A toolkit and benchmark study for FRET-restrained high-precision structural modeling. Nature methods, 9(12), pp.1218-1225.


# Info

_Author(s)_: Stanislav Kalinin

_Maintainer_: `tpeulen`

_License_: [LGPL](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2 of the License, or (at your option) any later version.
