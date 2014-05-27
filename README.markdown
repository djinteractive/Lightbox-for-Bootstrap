#Lightbox for Bootstrap
Lightbox for Bootstrap aims to enable your users to view larger, higher resolution images just by clicking on an image, or group of images and designed to be implemented in Bootstrap with minimal markup.

##Why
I wanted a lightbox plugin that with minimal effort , would just work with the bootstrap framework. Unfortunately the existing bootstrap-lightbox plugin did not do that, requiring extra markup, buggy css and javascript, even setting up a collection of images to cycle through was complicated. Instead of messing around trying to get it to just work, I grabbed the original Lightbox plugin and with a little prodding, I had a lightbox up and running exactly how I wanted. This plugin is an extention of that effort, incorporating ideas from the exiting plugins and migrating it over to the Bootstrap framework.


##Markup
###Step 1
Include the CSS and Javascript files.
````html
<link href="css/bootstrap.lightbox.css" rel="stylesheet" media="screen">
<script src="js/bootstrap.lightbox.js"></script>
````
###Step 2
Add the data-toggle="lightbox" attribute to the thumbnails class element.
````html
<ul class="thumbnails" data-toggle="lightbox"></ul>
````
###Step 3
Link to a larger image with a href="img/image-1.jpg" link or data-target="img/image-1.jpg" for each thumbnail class element.
````html
<a href="img/image-1.jpg" class="thumbnail"></a>
````
````html
<div data-target="img/image-1.jpg" class="thumbnail"></div>
````
###Optional
####Add a Title
````html
<a href="img/image-1.jpg" title="Image 1" class="thumbnail"></a>
````
````html
<div data-target="img/image-1.jpg" data-title="Image 1" class="thumbnail"></div>
````
####Add a Link to the Title
````html
<a href="img/image-1.jpg" title="Image 1" data-title-link="http://google.com" class="thumbnail"></a>
````
####Add a Description
````html
<a href="img/image-1.jpg" data-description="Lorem ipsum dolor" class="thumbnail"></a>
````

##Requirements
jQuery v1.72+ [http://jQuery.com/](http://jQuery.com/)

Bootstrap [http://twitter.github.com/bootstrap/](http://jQuery.com/)

##License
Licensed under the Creative Commons Attribution 2.5 License - [http://creativecommons.org/licenses/by/2.5/](http://creativecommons.org/licenses/by/2.5/)
* Free for use in both personal and commercial projects.
* Attribution requires leaving author name, author homepage link, and the license info intact.

##Thanks
Based on the original Lightbox 2 by [Lokesh Dhakar](http://www.lokeshdhakar.com)

##Alternatives
Bootstrap - Lightbox [http://jbutz.github.com/bootstrap-lightbox/](http://jbutz.github.com/bootstrap-lightbox/)

Lightbox 2 [http://lokeshdhakar.com/projects/lightbox2/](http://lokeshdhakar.com/projects/lightbox2/)
