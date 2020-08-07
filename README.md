# GMT-plotting
Collection of GMT (Generic Mapping Tools) scripts and files (including digitized map content, colormaps, grid files etc.). All scripts should run with **GMT 5.2.1** or higher. Each directory in this repository represents a single stand-alone application (individual manuals in pdf format are included as well):

**Update:** from time to time I will add Jupyter Notebooks to each directory in which I use **PyGMT**, a Python interface for GMT (**_Uieda & Wessel, 2017_**) to generate the individual maps and plots (see the :arrow_forward: symbol).

- [001_map_equidist_EQ](https://github.com/michaelgrund/GMT-plotting/tree/master/001_map_equidist_EQ): plotting global seismicity between 1960 and 2019 on equidistant map :arrow_forward: [Jupyter Notebook](https://github.com/michaelgrund/GMT-plotting/tree/master/001_map_equidist_EQ/pygmt_jupyter_notebook)
- [002_map_equidist_EQ_GCMT](https://github.com/michaelgrund/GMT-plotting/tree/master/002_map_equidist_EQ_GCMT): plotting focal mechanisms ("beach balls") of the global seismicity between 1964 and 2019 on equidistant map
- [003_map_seafloor_ages](https://github.com/michaelgrund/GMT-plotting/tree/master/003_map_seafloor_ages): plotting the ages of oceanic lithosphere on a global map :arrow_forward: [Jupyter Notebook](https://github.com/michaelgrund/GMT-plotting/tree/master/003_map_seafloor_ages/pygmt_jupyter_notebook)
- [004_map_splitting_database](https://github.com/michaelgrund/GMT-plotting/tree/master/004_map_splitting_database): plotting the content of the shear-wave splitting data base on a global map
- [005_map_equidist_siberia](https://github.com/michaelgrund/GMT-plotting/tree/master/005_map_equidist_siberia): plotting an equidistant map centered on NW Siberia (and raypaths)
- [006_map_SKS_SKKS_areas](https://github.com/michaelgrund/GMT-plotting/tree/master/006_map_SKS_SKKS_areas): visualizing of _SKS_-_SKKS_ pierce point areas in the D" layer
- [007_map_SKS_SKKS_pierce_points](https://github.com/michaelgrund/GMT-plotting/tree/master/007_map_SKS_SKKS_pierce_points): reproducing _SKS_-_SKKS_ pierce point figures of **_Grund & Ritter (2019)_**, Geology
- [008_map_scan_tectonic](https://github.com/michaelgrund/GMT-plotting/tree/master/008_map_scan_tectonic): visualizing geological and tectonic content of Fennoscandia :arrow_forward: [Jupyter Notebook](https://github.com/michaelgrund/GMT-plotting/tree/master/008_map_scan_tectonic/pygmt_jupyter_notebook)

If you make use of the content in this repository please acknowledge GMT (e.g. **_Wessel et al., 2013_**) as well as my PhD thesis in whose framework several of the figures were developed:

- **_Grund, M. (2019)_**, Exploring geodynamics at different depths with shear wave splitting, Dissertation, Karlsruhe Institute of Technology (KIT), https://doi.org/10.5445/IR/1000091425 

**I provide these GMT examples in the hope that they will be useful for other students, scientists or interested map creators.**

Final figure outputs of a few examples are shown below. Details and further references can be found in the individual directories. 

![PLOT_GMT_all](https://user-images.githubusercontent.com/23025878/59599891-f439ce00-90ff-11e9-82be-5e324fbcc893.png)

References

- **Wessel, P., Smith, W. H. F., Scharroo, R., Luis, J., & Wobbe, F. (2013)**, Generic mapping tools: improved version released. Eos, Transactions American Geophysical Union, 94(45), 409-410, https://doi.org/10.1002/2013EO450001
- **Uieda, L. & Wessel, P. (2017)**,  A modern Python interface for the Generic Mapping Tools. AGU Fall Meeting Abstracts, Abstract IN51B‐0018.
