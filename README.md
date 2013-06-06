CropImageBottomAndFillWidth
===========================
I came across scenario where i need to fill an image in width wise and height wise it should crop.
There is lots of ways we can do. by getting the bitmap object and crop or scaling the image. 
That can be a good solution when we have to crop one or two images, but when we have lots of 
images say that image is getting displayed in list view then the crop or scaling the bitmap is not an ideal solution 
as it slows down the scrolling and it consumes lots of memory. In that case we can go with this solution i proposed.

