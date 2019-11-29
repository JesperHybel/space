# Resources for spatial computation in R
This is a collection of resources for spatial computation in R.

# SP and SF packages
A good place to begin is to build an understanding of the package sp and the package sf. Both introduce classes of objects and associated methods used for handling spatial data in R. These packages have standardized the use of spatial data in R. The sp and sf packages use different methodologies for integrating spatial data into R. The sp package introduced a coherent set of classes and methods for handling spatial data in 2005.

## Definition of Spatial data
Let a data set be i=1,...,N observations on some attributes K attributes such that x = [x(i1),...,x(iK)]. In spatial data an extra feature
s(i) is added for each observation. This feature captures the location in space associated with the observation. Such locations could be defined as points, lines, polygons etc.  

## SP package
The sp package provides classes and methods for dealing with spatial data in R. The spatial data structures implemented include points, lines, polygons, rings and grids; each of them with or without attribute data. The classes are S4 classes. 

The sp package has an easily accesible introductory vignette called sp: classes and methods for spatial data
can be downloaded from CRAN at
https://cran.r-project.org/web/packages/sp/index.html

## SF package
The sf package talks about features having attributes as well as geometry (locations in space). The introductory vignette posted at https://cran.r-project.org/web/packages/sf/vignettes/sf1.html provides a table of the available classes and methods. The methods are available in R by the command methods(class = "sf")

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
