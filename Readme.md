# Simple image processing 
 ### Bitmap Playground
 Complete a simple unfinished UI application which allows the application of image filters
 and displays the results.
 
 ### 1. Implement a greyscale filter
 Implement a greyscale filter. There are several possibles formulas for computing
 greyscale images, you are free to choose any.
 
 ### 2. Implement a moving average filter
 Implement a moving average filter, as follows: The value of each output pixel at the
 position *output(x, y)* is the average value of the input pixel *input(x, y)* and the 4 pixels
 left, right, above and below it. If the input pixel lies at the border, its value may remain
 the same.

 ### 3. Extract the filters to an external project
 Extract IFilter and all of its implementations to an a separate dll project and reference
 it from the main project.
