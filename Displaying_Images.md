##Displaying images on Newsfeed, Products 

We show images uploaded by users on the following areas.

No. | Area | Description | change 
--- | --- | --- | ---
1 | Newsfeed | showing only one image in a post | see the rules
2 | Products on profile | Thumbnails of products | -
3 | Products | Thumbnails of products | -
4 | Products on Company | Thumbnails of products | -  
5 | A product detail | Max 4 images including the main image | see the rules  

###Rules on Newsfeed 
1. The maximum size of a box on Newsfeed is 600 x 800px 
2. The maximum width for actual images is 568px. The maximum size of images should be 568 x 758(757.333333) fit into 600 x 800 px 
2. The height of images is flexible in w568 x h758px 
3. No crop on images --> to understand the context of images  

**Note that this rule applies to seeing images(Displaying only) the images in our server should be bigger than 568 x 758px  --> saved as 1632 x 1224 px if images are bigger than 1632 x 1224** 

###Examples 
This is an example list how various images are displayed on Newsfeed. 

No. | Real Image Size | Display Image Size (Maximum: width 568px x height 758px) 
--- | --- | --- 
1 | 100 x 100 | 100 x 100
2 | 200 x 100 | 200 x 100
3 | 600 x 100 | 568 x 95(94.66) 
4 | 800 x 100 | 568 x 71
5 | 600 x 1000 | 455(454.8) x 758 
6 | 1024 x 768 | 568 x 426
7 | 2000 x 800 | 568 x 228(227.2) 
8 | 150 x 2000 | 57(56.85) x 758
9 | 5344 x 3008 | 568 x 320(319.71)

####1 - w100 x h100 
 ![100_100](https://github.com/isotype/STUFF/blob/master/Img/100_100.png)
 
####2 - w200 x h100 
![200_100](https://github.com/isotype/STUFF/blob/master/Img/200_100.png)

####3 - w600 x h100
![600_100](https://github.com/isotype/STUFF/blob/master/Img/600_100.png)

####4 - w800 x h100
![800_100](https://github.com/isotype/STUFF/blob/master/Img/800_100.png)

####5 - w600 x h1000
![600_1000](https://github.com/isotype/STUFF/blob/master/Img/600_1000.png)

####6 - w1024 x h768
![1024_768](https://github.com/isotype/STUFF/blob/master/Img/1024_768.png)

####7 - w2000 x h800
![2000_800](https://github.com/isotype/STUFF/blob/master/Img/2000_800.png)

####8 - w150 x h2000
![150_2000](https://github.com/isotype/STUFF/blob/master/Img/150_2000.png)

####9 - w5344 x h3008
![5344_3008](https://github.com/isotype/STUFF/blob/master/Img/5344_3008.png)

###Rules on a product detail 
The same as rules on Newsfeed but when clicking an image the larger image pops up. 
Products can have 5 images but by design only 1 image can be enlarged (600 x 800) 
and the other 4 images are shown as small. Without the image viewer function (seeing large images by clicking) the current design doesn't look functional.
But I don't think we have much time to add the image viewer function on the product detail page. The image viewer function will be added after the launch(10/30). 

