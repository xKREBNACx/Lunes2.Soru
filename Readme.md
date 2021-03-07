# Simple image processing 
 ### Bitmap Playground
 Complete a simple unfinished UI application which allows the application of image filters
 and displays the results.
 
 ### 1. Open the project 02_BitmapPlayground
 Familiarize yourself with the project. There is already one filter function available
 that removes the red component from the image. Try it out. Identify the parts marked
 with “TODO” in the source code.
 ![2](https://user-images.githubusercontent.com/18269686/60724689-a5c16780-9f26-11e9-857f-436ab79852df.png)
 
 ### 2. Implement a greyscale filter
 Implement a greyscale filter. There are several possibles formulas for computing
 greyscale images, you are free to choose any.
 ![1](https://user-images.githubusercontent.com/18269686/60721030-2333aa80-9f1c-11e9-8756-546825fe98ba.png)
 
 ### 3. Implement a moving average filter
 Implement a moving average filter, as follows: The value of each output pixel at the
 position *output(x, y)* is the average value of the input pixel *input(x, y)* and the 4 pixels
 left, right, above and below it. If the input pixel lies at the border, its value may remain
 the same.
 ![2](https://user-images.githubusercontent.com/18269686/60721072-452d2d00-9f1c-11e9-9bda-bce40db4c607.png)

 ### 4. Extract the filters to an external project
 Extract IFilter and all of its implementations to an a separate dll project and reference
 it from the main project.
