# GMT-plotting
Collection of GMT (Generic Mapping Tools) scripts and files including digitized map content etc. All scripts should run with **GMT 5.2.1** or higher. Each directory in this repository represents a single stand-alone application (individual manuals in pdf format are included as well):

- [GMT_gen_equidist_EQ](#p00): plotting global seismicity between 1960 and 2019 on equidistant map
- [GMT_scan_SKS_SKKS_areas](#p1): visualizing of SKS-SKKS pierce point areas in the D" layer
- [GMT_scan_SKS_SKKS_pierce_points](#p21): reproducing SKS-SKKS pierce point figures of Grund & Ritter (2019), Geology
- [GMT_scan_split_equidist_Siberia](#p22): plotting an equidistant map centered on NW Siberia (and raypaths)
- [GMT_scan_split_colorwheel](#p2): visualizing shear wave splitting results (color-coded with respect to source region)
- [GMT_scan_tectonic](#p3): visualizing geological and tectonic content of Fennoscandia

If you make use of the content in this repository please acknowledge GMT (e.g. **_Wessel et al., 2013_**) as well as my PhD thesis in whose framework several of the figures were developed:

- **_Grund, M. (2019)_**, Exploring geodynamics at different depths with shear wave splitting, Dissertation, Karlsruhe Institute of Technology (KIT), https://doi.org/10.5445/IR/1000091425 

<a name="p00"></a>
### GMT_gen_equidist_EQ

Script and files for plotting the global seismicity between 01/01/1960 and 01/05/2019 on a map with equidistant projection.
The following colormaps are included in the download package:

  1) Scientific colormaps by F. Crameri (Zenodo. http://doi.org/10.5281/zenodo.1243862)
    (see and download here: http://www.fabiocrameri.ch/colourmaps.php)

  2) MatPlotLib colormaps converted to GMT's cpt format (see and download here: http://soliton.vm.bytemark.co.uk/pub/cpt-city/mpl/index.html)





![EQequidistPLOT](https://user-images.githubusercontent.com/23025878/58618395-d9bfc200-82c2-11e9-8432-8299a18c3f33.png)


<a name="p1"></a>
### GMT_scan_SKS_SKKS_areas

Script and files for visualizing SKS-SKKS pierce point areas in the D" layer around a network in Fennoscandia (see final figure below).

![MapScandi_SKS_SKKS](https://user-images.githubusercontent.com/23025878/57453757-7b756580-7267-11e9-8618-c0f51034ef4b.png)

### GMT_scan_SKS_SKKS_pierce_points
<a name="p21"></a>

![GMT_SKS_SKKS_GR2019](https://user-images.githubusercontent.com/23025878/58184186-ea63ad00-7cb0-11e9-99b7-140df5103785.png)

<a name="p22"></a>
### GMT_scan_split_equidist_Siberia

Script and files for plotting an equidistant map centered on NW Siberia as well as raypaths from earthquake source locations to different seismic recording networks (see final figure below).
Used station and event information is freely available for the public  via ......

![MAP_Siberia](https://user-images.githubusercontent.com/23025878/57537067-cf567c00-7345-11e9-9ab0-68dbdd6d2220.png)


<a name="p2"></a>
### GMT_scan_split_colorwheel

Script and files for visualizing shear wave splitting results (color-coded with respect to source region) in Fennoscandia (see final figure below).

![SWS_MAP_Fenno_0_360](https://user-images.githubusercontent.com/23025878/57454697-bbd5e300-7269-11e9-9860-b71d8c557fce.png)

<a name="p3"></a>                        
### GMT_scan_tectonic

Script and files for visualizing geological and tectonic content of Fennoscandia (see final figure below). Content was partly digitised using Didger (R) (Golden Software, LLC) based on the following references:

Geological units are modified after Fig. 1 of:
- **Högdahl et al. (2004)**, Geological Survey of Finland, Special Paper 37, The Transscandinavian Igneous Belt (TIB) in Sweden: a review of its character and evolution

Tornquist zone is modified from paper:
- **Wylegalla et al. (1999)**, Tectonophysics 314, Anisotropy across the Sorgenfrei-Tornquist Zone from shear wave splitting, https://doi.org/10.1016/S0040-1951(99)00252-8

Major shear zones, faults and inferred paleo-subduction zones are modified after Figs. 1 & 2 of:
- **Korja & Heikkinen (2005)**, Precambrian Research 136, 241-268 The accretionary Svecofennian orogen-insight from the BABEL profiles, https://doi.org/10.1016/j.precamres.2004.10.007


![Scan_plotcont_MAP](https://user-images.githubusercontent.com/23025878/57081965-174a2300-6cf6-11e9-8e85-34d4c71c302a.png)
