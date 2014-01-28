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
* username: this is the username of your PicasaWeb account
* photosize: the size to display single images
* columns: the amount of columns to display all albums and all images in an album
* nextText: the text of the 'next' link
* previousText: the text of the 'previous' link
* albumText: the text of the 'album' link
* autoplay: true if you want videos to start playing automatically
	
###Upcoming features
When I find the time, I would like to add:
* Flash support for videos (working on it now, experimental)
* Add more options for translation, link texts, link images (i.e. for previous and next links),...
* Easily show just one album
* Easily show a slideshow (that might be a separate script)
* Change usage so you don't have to add the code in your head tag, but anywhere you want the albums to appear.
* A better way of passing options (not via global variables)

###Origin

The script is based on the pwa script by Jesse Berman and Dieter Raber. The modifications I made were mainly to support videos. Afterwards, extras were added like using divs and css instead of tables.

###My contact details:
* [Twitter](http://www.twitter.com/petermorlion)
* [GitHub](http://github.com/petermorlion)
* [Blog](http://petermorlion.blogspot.com)

Dieter Raber's email address is mentioned in the script (dieter@dieterraber.net), but I couldn't reach him (my emails bounced).