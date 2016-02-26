# Clean Bootstrap showroom HTML theme
## Prepared to use with Datarhei/Restreamer to get a clean showroom website for [Datarhei/Restreamer](https://datarhei.github.io/restreamer).  
This template features various content sections for Datarhei direct streaming, YouTube-Live, Usteam, a Contact section and a Google Maps section with a custom map marker. The snapshot is used as dynamic background via CSS. 

[Download](https://github.com/datarhei/showroom-html-theme/archive/gh-pages.zip) and start modifying index.html and graylog.css. Get it running in a few minutes just adding your IP or DynDNS with a text editor or your favourite HTML tool. Upload all files on your webserver and start streaming without streaming provider.

<img src="https://datarhei.github.io/restreamer/img/showroom-theme-scr.jpg" width="640" height="360">

##Features

* Datarhei/Restreamer iframe for direct streaming
* Dynamic backgrounds via live snapshot
* YouTube-Live section
* Ustream section
* Contact section
* Google Maps (default deactivated)

## Requirements
* Running Datarhei/Restreamer with working video input. [https://datarhei.github.io/restreamer](https://datarhei.github.io/restreamer)

## Getting started with the HTML theme

To use this theme, choose one of the following options to get started:
* Download the latest release on GitHub
* Fork this repository on GitHub

## Add your Datarhei/Restreamer video player
* Add your IP or dynamic DNS (dont forget the port!) to the index.html in root directory of the theme
* Look at the code comments marked with <!-- --> to find where to add the code

Optional: 
* Add your YouTube-Live ID for livestreaming in the YouTube section
* Add your Ustream URL in the section for ustream
* Change Contact information
* If you dont need Ustream or YouTube delete or uncomment this both sections and do not forget to do the same in the navigation.

## Add Datarhei/Restreamer snapshot as dynamic background
* The dynamic background ist configurated in the /css/grayscale.css
* Put your IP or dynamic DNS at the intro section and ustream section to use the snapshot as background
* Look at the code comments to find the right place.

---
**Datarhei Hint ☺ ►**  Do not forget portforwarding port :8080 to your Datarhei/Restreamer. This allows the video player on your website to stream the video from the local Restreamer application.

---
## Bugs and Issues

Have a bug or an issue with this theme? [Open a new issue](https://github.com/datarhei/showroom/issues) here on GitHub.

## Credits
Datarhei modified the original Grayscale template.  
Thank you to David Miller for the sweet HTML theme. 

Grayscale by [Start Bootstrap](http://startbootstrap.com/) - [Grayscale](http://startbootstrap.com/template-overviews/grayscale/)  

[Grayscale](http://startbootstrap.com/template-overviews/grayscale/) is a multipurpose, one page HTML theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This template features various content sections and a Google Maps section with a custom map marker.    

Start Bootstrap was created by and is maintained by David Miller, Managing Parter at [Iron Summit Media Strategies](http://www.ironsummitmedia.com/).  

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller  

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).  

Copyright and License   

Copyright 2013-2015 Iron Summit Media Strategies, LLC. Code released under the [Apache 2.0](https://github.com/IronSummitMedia/startbootstrap-grayscale/blob/gh-pages/LICENSE) license.
