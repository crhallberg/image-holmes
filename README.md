## Image Holmes

Image Holmes was created to fill the apparent gap that advanced image viewers either zoom OR rotate, not both. Thus! Created for the [VuFind](http://www.vufind.org) Open Source Project.

## Dependencies
 * [jQuery UI](http://www.jqueryui.com)
 * [mousewheel plugin](https://github.com/brandonaaron/jquery-mousewheel) by [Brandon Aaron](http://www.brandonaaron.net)
 * img-rotate plugin by [Austen Hoogen](http://www.austenhoogen.com)
 * inspector.css
 
## Using Holmes

You need to include the dependent scripts and the included stylesheet.

This plugin has only one function:

	$(container).inspector(img-src);
                 ^^^^^^^^^
				 
This is used for both initializing with a first image and replacing the image (don't worry, doesn't reinitialize). As of this post, the plugin has only been tested with divs, but it's assumed this will work with any element that displays as a block. The container does not need to contain anything special, or anything at all!

## About the Author

[Chris Hallberg](http://www.crhallberg.com) is a graduate assistant and Javascript ninja. This is his first github repository so he whole heartedly thanks you for coming by! He also likes talking in third-person.

## Other Credits

 * Arrow images from Wikipedia (temporary)