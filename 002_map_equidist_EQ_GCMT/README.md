## 002_map_equidist_EQ_GCMT

Script and files for plotting the focal mechanisms of the global seismicity between 28/01/1964 and 31/01/2019 on a map with equidistant projection (see final figure below). 
Earthquake data is freely available and was downloaded from the International Seismological Centre (ICS, http://www.isc.ac.uk).
Colormaps from (or based on) the following sources are included in the download package:

  1) Scientific colormaps by F. Crameri (Zenodo. http://doi.org/10.5281/zenodo.1243862)
    (see and download here: http://www.fabiocrameri.ch/colourmaps.php)

  2) Matplotlib colormaps converted to GMT's cpt format (see and download here: http://soliton.vm.bytemark.co.uk/pub/cpt-city/mpl/index.html)

To generate the map (using the viridis colormap) just run the script via the command line:

```console
user@seisPC:~$ ./GMT_EQglob_BFO_GCMT.gmt
```
In general, first you have to make the script executable via:
```console
user@seisPC:~$ chmod +x GMT_EQglob_BFO_GCMT.gmt
```
**Detailed information and instructions for the individual steps to generate the final figure can be found in the manual (pdf-file).**

![EQglob_BFO_GCMT](https://user-images.githubusercontent.com/23025878/60886227-b1c46680-a251-11e9-968c-80353174f7ab.png)
