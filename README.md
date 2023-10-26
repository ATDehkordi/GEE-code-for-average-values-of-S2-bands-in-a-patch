# GEE code for extracting the mean values of S2 satellite images bands in a patch

## This is a Java code in Google Earth Engine (GEE)
![GoogleEarthEngine](https://github.com/ATDehkordi/GEE-code-for-average-values-of-S2-bands-in-a-patch/assets/34648501/c7a3bc36-f913-4c6e-9962-70bc5b0176c9)

### To extract the mean values of Sentinel-2 (S2) L2A satellite imageries over a nxn patch.
The inputs are:
* Location of in-situ ground station,
* Study region
* Final patch size

The output will be:
* A feature collection which contain k features (number of cloud-free S2 images over the region), each of which has 10 values (spectral bands)

