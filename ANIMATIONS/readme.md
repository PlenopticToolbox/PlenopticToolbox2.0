# Animation

This page is just as an explanation to create small gifs from images (viewpoints, disparity or so) in order to show what can be done with the images.

Sample GIF               |  Sample GIF          |  Sample GIF          |
:-------------------------:|:-------------------------:|:-------------------------:|
![](https://github.com/PlenopticToolbox/PlenopticToolbox2.0/blob/master/ANIMATIONS/small_ani_dragon.gif)  |  ![](https://github.com/PlenopticToolbox/PlenopticToolbox2.0/blob/master/ANIMATIONS/small_ani.gif) | ![](https://github.com/PlenopticToolbox/PlenopticToolbox2.0/blob/master/ANIMATIONS/small_ani_glasses.gif) |  

Here a downscaled version of a gif created with the script `gen_gif`

the script `gen_gif` is a shell script to generate a gif from the views generated from the perspective_views.py script, for example.
It uses the [`convert` command](https://imagemagick.org/script/convert.php) that is part of the [ImageMagick](https://www.imagemagick.org/) package, so you need to install that if you want to use it.

it should be run as 

`sh gen_gif ~/complete_path_to_the_root_folder_where_you_will_find_the_Views_folder(without_Views_in_the_path)`

It should output information about what is trying to do.

