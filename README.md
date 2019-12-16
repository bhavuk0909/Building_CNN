# Building_CNN

Steps to be followed are:

1. Convolution: Mathematically, convolution can be understood as a combined integration of 2 functions and somehow shows us the way how      one function alters or modifies the other one. Intuitively, we can say that convolution helps in making the size of the image smaller      as we use feature detector on the input image. This can be further use for blurring, embossing, edge detection and much more.

2. Max Pooling: Suppose we have multiple images of any object but ultimately the images are of a single object, then here comes the role      of max pooling as it tries to teach our network that despite all differences, they are all images of that particular object. Spatial      Variance comes here in the role.

3. Flattening: To flatten our pooled feature map into a column like in order to input the data in the CNN and we ends with a long vector      of the data inputted.

4. Full Connection (Fully Connected Layers): It can be understood as all the neurons of the layer are connected to all the neurons of the    next layer and so on.
