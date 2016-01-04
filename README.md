# static-website-copy

This is a static copy made January 4, 2016 of http://www.housingprototypes.org

It is intended to serve as a basis for preservation of content available at http://www.housingprototypes.org authored by Roger Sherwood, Emeritus Professor of Architecture at University of California.

To the best of my knowledge the Roger Sherwood is the copyright holder for the content presented at this time.

## Directories

+ www.housingprototypes.org holders a raw copy made with wget of the website as it of January 4, 2016
+ site holds a version that can be served static files via a webserver (e.g. Nginx, Apache, NodeJS, or other static webserver
    + Search box functionality does not work at this time (though could be made via [Lunr.js](http://lunrjs.com/))
    + The paging in browsering is fixed since this is a static copy and dynamic page generation is not an option

## Outstanding issues

The static copying process renders allot of duplicate content as individual HTML files. This makes it problematic to continue authoring.
It does allow hosting a static version of the webstite as well as re-rendering the content to an eBook (the current
objective).  In an ideal world the current dynamically generate content would be processed browser side via JavaScript replacing the functionality
historically implemented via Zope and MySQL. If all goes as planned the searchbox functionality will be implemented this way using the Lunr.js 
browser library.  Likewise integrating Solr or Exlastic search to provide this functionilty would be an option if a funding source was identified.

## Current Project Goals

+ Host a preserved copy of the site as a static website at http://housingprototypes.github.io
+ Fix broken links in static website
+ Swap current searchbox for lunr.js version
+ Work with the author replace any broken images in January 2016 copy
+ Convert website into an eBook of some sort for the author and his family.

## COPYING

Copyright on this work is retained by Rodger Sherwood, Professor Emeritus of the University of Southern California's School of Architecture. If you are interested repurposing this content contact Rodger.


