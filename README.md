# booth-cam
Small webpage to focus the CMU Spring Carnival camera on KGB's booth

This repo holds the two html files for the KGB booth cam page. One is for the
live cam during carnival and one is for the timelapse posted the rest of the
year. The appropriate page should be symliked to by booth.html in the parent
directory on the web server. That page is at cmukgb.org/activities/booth.html
and booth.cmukgb.org. This pages is embedded on the WordPress site at
cmukgb.org/booth to make it look prettier.

To keep this up to date:
* Update the Facebook link on the WordPress site each year.
* Switch the symlink to live before build week and back after Carnival.
* Update the video dimensions. In both the timelapse and the live page, change
  the “top” and “left” attributes on the video. The easiest way to find them is
  probably to search for “px” or “top” or “left.” They should be some large
  negative value. Unfortunately you just have to use trial and error and keep
  reloading the page in your browser until KGBooth is in frame. Make sure to
  update these values in two places in the live page (mobile and non-mobile)
  and one place in the timelapse page.
* Update the video source. In both pages, change the youtube link to this
  year’s link. You can search for “youtube” to find what to change. Get this
  year’s link from carnival.activitiesboard.org. Make sure autoplay is on.
  Also, if Spring Carnival Committee (or AB Tech) keeps hosting the
  non-youtube, image-based version, update that link too. You may not have to
  change anything because the current link is
  http://carnival.activitiesboard.org/image.jpg which seems future-proof.

