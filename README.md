# riabcham-data
Prepare data for cellprofiler

This repository is for files related to my cellprofiler pipeline.

# Setup
**Cellprofiler**

Download and install cellprofiler (v4.2.6) from their website. [link](https://cellprofiler.org/)

Set location of classifier models in "ClassifyObjects" module to location on your machine.

**Required Python Packages**
1. Pillow

``` 
pip install pillow
```
2. Tensorflow

``` 
pip install tensorflow
```
3. Stardist

``` 
pip install stardist
```

See [stardist repository](https://github.com/stardist/stardist) for more details on setting up stardist.

Stardist has trouble installing on Mac M1/M2 systems. See [stardist issue #19](https://github.com/stardist/stardist/issues/19).

*If using Windows, download python from the [website](https://www.python.org/downloads/). The microsoft store installation does not properly set up pip.

**RStudio**

Instructions on setting up RStudio can be found [here](https://rstudio-education.github.io/hopr/starting.html).

Set the "use_python" function to the location of python on your machine in stardist_v1.rmd.

Go [here](https://github.com/ttimbers/intro-to-reticulate/blob/main/setup-instructions/macos_install_python.md) for troubleshooting issues with the reticulate package.

This pipeline should work on python >= 3.8. I used 3.8 for compatibility with cellprofiler v4.2.6 although cellprofiler v5 will be >= 3.9.




*The current pipeline no longer uses ilastik. See original version for TIF to h5 conversion and running ilastik.

