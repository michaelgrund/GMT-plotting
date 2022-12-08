# GMT-plotting
Collection of **GMT** ([Generic Mapping Tools](https://www.generic-mapping-tools.org/)) scripts and files (including digitized map content, colormaps, grid files etc.). All scripts should run with GMT versions **>= 5.2.1** and **< 6.0.0** . Each directory in this repository represents a single stand-alone application (individual manuals in pdf format are included as well):

Some directories include Jupyter Notebooks in which I use [**PyGMT**](https://www.pygmt.org), a Python interface for GMT ([**_Uieda et al., 2022_**](https://zenodo.org/record/6702566#.YveVDRzP02w)) to generate the individual maps and plots (see the :arrow_forward: symbol).

- [001_map_equidist_EQ](https://github.com/michaelgrund/GMT-plotting/tree/master/001_map_equidist_EQ): plotting global seismicity between 1960 and 2019 on equidistant map :arrow_forward: [Jupyter Notebook](https://github.com/michaelgrund/GMT-plotting/tree/master/001_map_equidist_EQ/pygmt_jupyter_notebook/pygmt_plot_equidist_EQs.ipynb)
- [002_map_equidist_EQ_GCMT](https://github.com/michaelgrund/GMT-plotting/tree/master/002_map_equidist_EQ_GCMT): plotting focal mechanisms ("beach balls") of the global seismicity between 1964 and 2019 on equidistant map
- [003_map_seafloor_ages](https://github.com/michaelgrund/GMT-plotting/tree/master/003_map_seafloor_ages): plotting the ages of oceanic lithosphere on a global map :arrow_forward: [Jupyter Notebook](https://github.com/michaelgrund/GMT-plotting/tree/master/003_map_seafloor_ages/pygmt_jupyter_notebook/pygmt_seafloor_ages.ipynb)
- [004_map_splitting_database](https://github.com/michaelgrund/GMT-plotting/tree/master/004_map_splitting_database): plotting the content of the shear-wave splitting data base on a global map
- [005_map_equidist_siberia](https://github.com/michaelgrund/GMT-plotting/tree/master/005_map_equidist_siberia): plotting an equidistant map centered on NW Siberia (and raypaths)
- [006_map_SKS_SKKS_areas](https://github.com/michaelgrund/GMT-plotting/tree/master/006_map_SKS_SKKS_areas): visualizing of _SKS_-_SKKS_ pierce point areas in the D" layer :arrow_forward: [Jupyter Notebook](https://github.com/michaelgrund/GMT-plotting/blob/master/006_map_SKS_SKKS_areas/pygmt_jupyter_notebook/pygmt_SKS_SKKS_areas.ipynb) 
- [007_map_SKS_SKKS_pierce_points](https://github.com/michaelgrund/GMT-plotting/tree/master/007_map_SKS_SKKS_pierce_points): reproducing _SKS_-_SKKS_ pierce point figures of [**_Grund & Ritter (2019)_**](https://doi.org/10.1130/G45514.1), Geology
- [008_map_scan_tectonic](https://github.com/michaelgrund/GMT-plotting/tree/master/008_map_scan_tectonic): visualizing geological and tectonic content of Fennoscandia :arrow_forward: [Jupyter Notebook](https://github.com/michaelgrund/GMT-plotting/tree/master/008_map_scan_tectonic/pygmt_jupyter_notebook/pygmt_map_tectonic_fenno.ipynb)
- [009_paper_GR2020](https://github.com/michaelgrund/GMT-plotting/tree/master/009_paper_GR2020): :arrow_forward: Jupyter Notebooks to reproduce some figures presented in our paper [**_Grund & Ritter (2020)_**](https://doi.org/10.1093/gji/ggaa388), GJI
- [010_paper_RFSG2022](https://github.com/michaelgrund/GMT-plotting/tree/master/010_paper_RFSG2022): :arrow_forward: Jupyter Notebook to reproduce figure 1 presented in our paper [**_Ritter, Fröhlich, Sanz Alonso & Grund (2022)_**](https://doi.org/10.1007/s10950-022-10112-w) Journal of Seismology

---

If you make use of the content in this repository please acknowledge GMT (e.g. [**_Wessel et al., 2013_**](https://doi.org/10.1002/2013EO450001); [**_2019_**](https://doi.org/10.1029/2019GC008515)), PyGMT ([**_Uieda et al., 2022_**](https://zenodo.org/record/6702566#.YveVDRzP02w)), our published papers and/or my PhD thesis in whose framework several of the scripts and notebooks were developed:

- **_Ritter, J.R.R., Fröhlich, Y., Sanz Alonso, Y. & Grund, M. (2022)_**, Short-scale laterally varying SK(K)S shear wave splitting at BFO, Germany – implications for the determination of anisotropic structures, Journal of Seismology, 26, 1137-1156, https://doi.org/10.1007/s10950-022-10112-w.

- **_Grund, M. & Ritter, J.R.R. (2020)_**, Shear-wave splitting beneath Fennoscandia - Evidence for dipping structures and laterally varying multilayer anisotropy, Geophysical Journal International, 223, 1525–1547, https://doi.org/10.1093/gji/ggaa388.

- **_Grund, M. & Ritter, J.R.R. (2019)_**, Widespread seismic anisotropy in Earth’s lowermost mantle beneath the Atlantic and Siberia, Geology, 47(2), 123–126, 
https://doi.org/10.1130/G45514.1.

- **_Grund, M. (2019)_**, Exploring geodynamics at different depths with shear wave splitting, Dissertation, Karlsruhe Institute of Technology (KIT), https://doi.org/10.5445/IR/1000091425. 

---

**Although I now work outside of academia as a [data scientist](https://innoplexia.com/das-team/), I provide these GMT/PyGMT examples and notebooks in the hope that they will be useful for other students, scientists or interested map creators.**

Final figure outputs of a few examples are shown below. Details and further references can be found in the individual directories. 

![PLOT_GMT_all](https://user-images.githubusercontent.com/23025878/59599891-f439ce00-90ff-11e9-82be-5e324fbcc893.png)

---

### References

- **_Uieda, L., Tian, D., Leong, W. J., Jones, M., Schlitzer, W., Grund, M., Toney, L., Yao, J., Magen, Y., Materna, K., Fröhlich, Y., Belem, A., Newton, T., Anant, A., Ziebarth, M., Quinn, J., & Wessel, P. (2022)_**, PyGMT: A Python interface for the Generic Mapping Tools, v0.7.0, Zenodo, https://zenodo.org/record/6702566.
- **_Wessel, P., Luis, J. F., Uieda, L., Scharroo, R., Wobbe, F., Smith, W. H. F. & Tian, D. (2019)_**, The generic mapping tools version 6. Geochemistry, Geophysics, Geosystems, 20(11), 5556-5564, https://doi.org/10.1029/2019GC008515.
- **_Wessel, P., Smith, W. H. F., Scharroo, R., Luis, J., & Wobbe, F. (2013)_**, Generic mapping tools: improved version released. Eos, Transactions American Geophysical Union, 94(45), 409-410, https://doi.org/10.1002/2013EO450001.
