# GMT-plotting
Collection of GMT (Generic Mapping Tools) scripts and files including digitized map content etc. All scripts should run with **GMT 5.2.1** or higher. Each directory in this repository represents a single stand-alone application (individual manuals in pdf format are included as well):

- [GMT_gen_equidist_EQ](https://github.com/michaelgrund/GMT-plotting/tree/master/GMT_gen_equidist_EQ): plotting global seismicity between 1960 and 2019 on equidistant map
- [GMT_scan_SKS_SKKS_areas](https://github.com/michaelgrund/GMT-plotting/tree/master/GMT_scan_SKS_SKKS_areas): visualizing of SKS-SKKS pierce point areas in the D" layer
- [GMT_scan_SKS_SKKS_pierce_points](https://github.com/michaelgrund/GMT-plotting/tree/master/GMT_scan_SKS_SKKS_pierce_points): reproducing SKS-SKKS pierce point figures of Grund & Ritter (2019), Geology
- [GMT_scan_split_equidist_Siberia](https://github.com/michaelgrund/GMT-plotting/tree/master/GMT_scan_equidist_Siberia): plotting an equidistant map centered on NW Siberia (and raypaths)
- [GMT_scan_tectonic](https://github.com/michaelgrund/GMT-plotting/tree/master/GMT_scan_tectonic): visualizing geological and tectonic content of Fennoscandia

If you make use of the content in this repository please acknowledge GMT (e.g. **_Wessel et al., 2013_**) as well as my PhD thesis in whose framework several of the figures were developed:

- **_Grund, M. (2019)_**, Exploring geodynamics at different depths with shear wave splitting, Dissertation, Karlsruhe Institute of Technology (KIT), https://doi.org/10.5445/IR/1000091425 

<a name="p00"></a>
### GMT_gen_equidist_EQ

Script and files for plotting the global seismicity between 01/01/1960 and 01/05/2019 on a map with equidistant projection (see final figure and alternative color schemes below). Earthquake data is freely available and was downloaded from https://earthquake.usgs.gov.
Colormaps from (or based on) the following sources are included in the download package:

  1) Scientific colormaps by F. Crameri (Zenodo. http://doi.org/10.5281/zenodo.1243862)
    (see and download here: http://www.fabiocrameri.ch/colourmaps.php)

  2) Matplotlib colormaps converted to GMT's cpt format (see and download here: http://soliton.vm.bytemark.co.uk/pub/cpt-city/mpl/index.html)

![EQequidistPLOT](https://user-images.githubusercontent.com/23025878/58618395-d9bfc200-82c2-11e9-8432-8299a18c3f33.png)


