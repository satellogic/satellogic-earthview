# Satellogic EarthView dataset

![satellogic-earthview](https://github.com/satellogic/satellogic-earthview/raw/main/docs/source/_static/img/dataset_samples.jpg) <br />

## Overview

This repository illustrates how to explore the Satellogic EarthView dataset hosted on AWS as part of the Open Data Registry Program.

To facilitate exploration, we provide a Jupyter Notebook, *satellogic-earthview_exploration.ipynb*. This notebook demonstrates how to download a Parquet file containing the relative path for all items together with their zone, region, date, and geometry.

Please note that the geometries have been reprojected to EPSG:4326. As a result, their bounds may not align perfectly with the original GeoTIFF files, which are stored in a UTM CRS, such as EPSG:32610.

## Requirements

In order to run the notebook you will need the following Python libraries

- Pyarrow
- Geopandas
- Folium
- Rasterio
- Pyproj

## Citation 

If you use our EarthView dataset in your research please consider citing:

```
@inproceedings{earthview2025,
                author={Velázquez, Diego and Rodríguez, Pau and Alonso, Sergio and Gonfaus, Josep M. and González, Jordi and, Richarte, Gerardo and Marín, Javier and Bengio, Yoshua and Lacoste, Alexandre},
                booktitle={2025 IEEE/CVF Winter Conference on Applications of Computer Vision Workshops (WACVW)}, 
                title={EarthView: A Large Scale Remote Sensing Dataset for Self-Supervision}, 
                year={2025}}  
```

## License

The dataset is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).  


## Support

For any questions or suggestions you can use the issues section or reach us at the following email addresses: javier.marin@satellogic.com or gera@satellogic.com
