# booth-cam
Small webpage to focus the CMU Spring Carnival camera on KGB's booth

This repo holds the two html files for the KGB booth cam page. One is for the
live cam during carnival and one is for the timelapse posted the rest of the
year. The appropriate page should be symliked to by index.html in the
`/var/www/booth-cam` directory on the web server.

That page is accessible at http://booth.cmukgb.org.
In the past, this page has been embedded on the 2013 WordPress site at
https://www.cmukgb.org/2013/?page_id=92 to make it look prettier.
Something similar could be done with https://www.cmukgb.org/booth/
on the 2019 version of the site.

To keep this up to date:
* Update the Facebook link on the WordPress site each year.
* Update the header on the WordPress site before and after Carnival. You can
  see the revision history to see what it was set to for past Carnivals.
* Update the date Carnival starts in the counter on the live page. Search for
  counter and the date should be visible and obvious.
* Switch the symlink to live before build week and back after Carnival.
* Update the video dimensions. In both the timelapse and the live page, change
  the “top” and “left” attributes on the video. The easiest way to find them is
  probably to search for “px” or “top” or “left.” They should be some large
  negative value. Unfortunately you just have to use trial and error and keep
  reloading the page in your browser until KGBooth is in frame. Make sure to
  update these values in the live page and in the timelapse page.
* Update the video source. In both pages, change the youtube link to this
  year’s link. You can search for “youtube” to find what to change. Get this
  year’s link from https://www.springcarnival.org or their
  [YouTube account](https://www.youtube.com/channel/UCU9POVg8y6XmdT_seh6nHDA).
  Make sure autoplay is on and, further, that the mute parameter is set
  so that autoplay actually works (at least on desktop).
