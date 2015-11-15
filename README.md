# ImageResizer

Image resizer is a Node.js web service for image resizing.

Image resizer accepts up to 3 params: width, height, url and respond with image resized (keeping proportions) to fit in width ✕ height.

For example: http://service-url.com/resize?width=400&url=http://www.wollemipine.co.uk/acatalog/Wallpaper_CollectorsEdition800x600.jpg
will resize this image of the size 800x600

![Original image 800x600](https://github.com/fealaer/image-resizer/blob/master/docs/images/Wallpaper_CollectorsEdition800x600.jpg)

to it's smaller version of the size 400✕300

![Resized image 400x300](https://github.com/fealaer/image-resizer/blob/master/docs/images/Wallpaper_CollectorsEdition400x300.jpg)
