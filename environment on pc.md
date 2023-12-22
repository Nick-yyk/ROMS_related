# Set the environments on PC
**oracle virtual box +ifort + oneapi(intel) + NetCDF4**

## 1. install oracle virtual box
https://www.bilibili.com/video/BV1aW411C7NR/?spm_id_from=333.999.0.0

## 2. Intel compiler
notice that the version of intel compiler needs to be earlier than 2023.0.0 (including 2023.0.0) or will meet some wired problem when running roms 

problem discussion: https://www.myroms.org/forum/viewtopic.php?t=6364

instruction: https://www.bilibili.com/read/cv15890857/

## 3. install NetCDF4
instruction: https://blog.csdn.net/qq_39970131/article/details/116861365 

find the packages as follow:

* zlib http://www.zlib.net/ 
* hdf5 https://portal.hdfgroup.org/display/support/HDF5+1.12.0#files
* netcdf-c https://www.unidata.ucar.edu/software/netcdf/
* netcdf-fortran https://www.unidata.ucar.edu/software/netcdf/
  ***
  If meet something wrong then download an early version may help.

## 4.Subversion download ROMS

 WikiROMS (myroms.org)![image](https://github.com/Nick-yyk/ROMS_related/assets/150812551/ad3a9a39-96e4-4963-95a9-ba5f64028ff7)

VPN might be needed if in mainlan China

## 5.Run ROMS case upwelling

https://blog.csdn.net/islandowner2017/article/details/119303181
