# ProteinPocketDetection

## Introduction
This is the source code for paper "Protein Pocket Detection via Convex Hull Surface Evolution and Associated Reeb Graph".<br />
This only supports Linux OS.<br />

## Dependencies
Make sure all the following libraries installed in your system.<br />

[Boost](https://www.boost.org/) <br /> 
Command: sudo apt-get install libboost-all-dev <br /> 
[OpenEXR](http://www.openexr.com/) <br /> 
Command: sudo apt-get install libopenexr-dev <br />
[TBB](https://www.threadingbuildingblocks.org/) <br /> 
Command: sudo apt-get install libtbb-dev <br />
[CGAL](https://www.cgal.org/) <br /> 
Command: sudo apt-get install libcgal-dev libcgal-qt5-dev <br />
[OpenVDB](http://www.openvdb.org/) <br /> 
Command: sudo apt-get install libopenvdb-dev <br />

## Building
1. Create a new folder under root directory<br />
2. Command "cmake .."<br />
3. Command "make"<br />

## Usage
**./CavityDetection** **obj_file** **xyzr_file** **minimum_depth** **minimum_area** **minimum_volume**<br />

**./CavityDetection**: the executable<br />
**obj_file**: molecular surface model obj file.<br />
**xyzr_file**: atoms information file, xyz coordinate and radius per line for each atom.<br />
**minimum_depth**: minimum required pocket depth<br />
**minimum_area**: minimum required pocket cross-section area<br />
**minimum_volume**: minimum required pocket volume.<br />
