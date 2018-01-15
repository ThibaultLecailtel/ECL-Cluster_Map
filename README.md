## Thibault Lecailtel

# Cluster Map

## 1. Definition

A cluster map helps represent dense pockets of data points using a single point. Each cluster is either relatively sized to or labelled with the number of points that have been grouped together.

Clusters are ideal in interactive maps where the user can drill down to see individual data points contained in a cluster. Cluster maps help reduce clutter when there are many overlapping data points in a small geography. Often, the clusters are updated depending on the zoom chosen by the user. 

For example, here is a map with hundreds of markers:

<img src="img/before.png" alt="before" width="600"/>

Instead, we use the following cluster map:

<img src="img/after.png" alt="after" width="600"/>

## 2. Recent example

There is no example of historical cluster maps because these maps are often interactive maps depending on several markers, thus they use recent technologies with clustering algorithms.

However, there are lots of examples of recent cluster maps. They are especially used by companies that have several stores on a territory.

For example, here is an extract of the cluster map of the Carrefour stores in France, on January 15th, 2018:

<img src="img/carrefour.png" alt="carrefour" width="600"/>


## 3. Variations

* **Natural**

Clusters have a natural appearance on the map. Location is used to control placement within the clustering grid. The original x,y map location of the cluster's founding data point is used for the location.

This is an example of natural clustering:

<img src="img/natural.png" alt="natural" width="600"/>

* **Grid**

The map is divided into squares of a certain size and the cluster marker is placed in the center of each applicable grid square. As zoom levels change, so do the clusters and their location on the map but they will maintain their grid-like appearance.

This is the intermediate step that uses a grid to create the clusters:

<img src="img/grid.png" alt="grid" width="600"/>

* **Different sizes and/or colors**

Different colors, shapes, and icons are useful for emphasizing clusters on the map. Clusters with a higher number count will stand out if given a larger size or a brighter color.

Here is a map where the color and the size of each cluster is proportional to the number of markers represented:

<img src="img/color.PNG" alt="color" width="600"/>

* **Pie charts**

Clusters can show the distribution of the different markers on a pie chart.

For example, here are clusters showing the number of UFO sightings in 2015 in the USA, and pie charts representing the different UFO shapes seen:

<img src="img/pie.PNG" alt="pie" width="600"/>

* **Average value**

Cluters can show the average value of the clustered markers.

For example, here are clusters showing the average incomes in the USA, along with pie charts showing the incomes' distribution:

<img src="img/average.PNG" alt="average" width="600"/>

## 4. Sources

* [Definition](https://blog.socialcops.com/academy/resources/7-techniques-to-visualize-geospatial-data/)
* [Pictures before and after clustering, and grid cluster](http://blog.batchgeo.com/map-clustering-demo-tutorial/)
* [Carrefour cluster map](https://www.carrefour.fr/magasin)
* [Cluster maps variations](http://maplarge.com/visual/clustering)
* [Pie chart cluster map](https://batchgeo.com/features/map-clustering/)
