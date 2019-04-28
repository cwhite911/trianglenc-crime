# Kepler.gl Lab

In this tutorial, you use Kepler.gl an open-source data visualization tool created by [Uber's data visualization team](http://vis.gl/) to visualize [crime data](https://data-ral.opendata.arcgis.com/datasets/raleigh-police-incidents-nibrs) in Raleigh, North Carolina using the city's [open data portal](https://data-ral.opendata.arcgis.com/).

![Final Product](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/finalProduct.gif)

### 1. Open kepler.gl in the browser at https://kepler.gl/ at click the "GET STARTED" button.

![Final Product](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/getstarted.png)

### 2. Load the Raleigh crime data to the map using the following URL from Raleigh's open data portal.

[Raleigh Crime Data](https://data-ral.opendata.arcgis.com/datasets/raleigh-police-incidents-nibrs)
```
https://opendata.arcgis.com/datasets/24c0b37fa9bb4e16ba8bcaa7e806c615_0.geojson
```

1. Click "Load Map using URL" tab 

2. Copy and paste the crime data URL where the text input says "File Url".

3. Fetch the data by pressing the "Fetch" button.
> Be patient the data will take a minute to load because it's ~250,000 points (~23.0 MB).

![Get Data](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/fetchData.png)

### 3. Now that the data is loaded your map should show crime points on the map with a randomly assigned color.

![Get Data](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/loadedData.png)


### 4. In the left panel find the point and polygon layers that were created by default and delete the polygon layer.

1. Move the cursor over the polygon layer and a trash can symbol will appear. 
2. Click the trash can to delete the layer.

![Delete Polygon Layer](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/deleteLayer.png)


### 5. Click on layer settings to expose the available marks and channels options.

![Layer Settings](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/layerSettings.png)

#### Marks

![Marks](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/marks.png)

#### Channels

> The type of mark will change the available channel options.

![Channels](https://raw.githubusercontent.com/cwhite911/trianglenc-crime/master/images/channels.png)






