>The testing points and training points are prepared by :
	1) create a labeled shapefiles of points
	2) convert the labeled shapefile to a raster (tif)
>The training tile and the testing tiles are clipped from the original image.

>The testing points and training tile should have equal number of rows and columns. The same applies to the testing points and the 
testing points. 

>The testing tile can be clipped to reduce the testing time and memory overload.

> CNN_prepare_training_data.ipynb prepares the training data
> FCN_training_tutorial.ipynb creates the FCN model and performs training
>FCN+TESTING_tutorial.ipynb tests the trained FCN model
