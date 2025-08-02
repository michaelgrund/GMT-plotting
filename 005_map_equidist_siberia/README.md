## 005_map_equidist_siberia

Script and files for plotting an equidistant map centered on NW Siberia as well as raypaths from earthquake source locations to different seismic recording networks (see final figure below).

To generate the map just run the script via the command line:

```console
user@seisPC:~$ ./MAP_Siberia_EQUDIST.gmt
```
In general, first you have to make the script executable via:
```console
user@seisPC:~$ chmod +x MAP_Siberia_EQUDIST.gmt
```
**Detailed information and instructions for the individual steps to generate the final figure can be found in the manual (pdf-file).**

Equivalent Python scripts using PyGMT can be found at
[009_deepdyn/03_scanarray/01_epidist_rays](https://github.com/yvonnefroehlich/gmt-pygmt-plotting/tree/main/009_deepdyn/03_scanarray/01_epidist_rays).


Used station and event information is freely available from:
- https://geofon.gfz-potsdam.de/ (ScanArray, Greenland)
- https://www.fdsn.org/networks/ (AlpArray, Russia)
- http://ds.iris.edu/ds/nodes/dmc/earthscope/usarray/ (USArray)
- https://earthquake.usgs.gov (events)

![MAP_Siberia](https://user-images.githubusercontent.com/23025878/57537067-cf567c00-7345-11e9-9ab0-68dbdd6d2220.png)
