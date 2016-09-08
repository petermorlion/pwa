** Update **

No longer maintained, see below for details.

##pwa

pwa is an easy-to use javascript library to display Google Picasa Web albums in your website.

###Use
Usage is easy (check the included example.html for an example). Include this javascript code in your head tag:

    <script type="text/javascript">
		username='gentlefoto'; // your PicasaWeb user name here 
		photosize='800'; 
		columns='4';
		nextText = 'next';
		previousText = 'previous';
		albumText = 'album';
		autoplay = true; // autoplay video
	</script>
    <script type="text/javascript" src="./pwa.js"></script>

###Options
Options are provided by declaring global variables. This is not a best-practice and I hope to change that in the future. Meanwhile, these are the available options:

* username: this is the username of your PicasaWeb account
* photosize: the size to display single images
* columns: the amount of columns to display all albums and all images in an album
* nextText: the text of the 'next' link
* previousText: the text of the 'previous' link
* albumText: the text of the 'album' link
* autoplay: true if you want videos to start playing automatically
* albumid: the id of an album if you want to display an album immediately (i.e. without showing the album overview first)
* photoid: the id of a photo if you want to display a photo immediately (i.e. without showing the contents of the album first). You must also specify the albumid to use this.
* galleryHomeText: the text to go back to the root level, showing all galleries
* viewGalleryInPicasaText: the text for a link to the gallery in Picasa
* viewAlbumInPicasaText: the text for a link to the album in Picasa
	
###Upcoming features
When I find the time, I would like to add:
* Add more options for translation, link texts, link images (i.e. for previous and next links),...
* Easily show a slideshow (that might be a separate script)
* Change usage so you don't have to add the code in your head tag, but anywhere you want the albums to appear.
* A better way of passing options (not via global variables)
* 

** Update **
Time moves on, interests change and needs evolve. I am no longer maintaining this library. Also, [Google is moving
away from Picasa Web Albums](http://googlephotos.blogspot.be/2016/02/moving-on-from-picasa.html), so this library
will become less and less relevant.

###Origin

The script is based on the pwa script by Jesse Berman and Dieter Raber. The modifications I made were mainly to support videos. Afterwards, extras were added like using divs and css instead of tables.

###My contact details:
* [Twitter](http://www.twitter.com/petermorlion)
* [GitHub](http://github.com/petermorlion)
* [Blog](http://petermorlion.blogspot.com)
