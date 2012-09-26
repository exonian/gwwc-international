Giving What We Can International
================================

A static site with styling based on a stripped-down version
of gwwc's upcoming v3 redesign.

Layout and media directories live outside of individual site
directories (which contain a site.yaml) and are symlinked
into each.


Install for development
-----------------------
1. pip install -r requirements.txt
2. cd into the required site directory
3. hyde serve to run local development server, which builds files on-demand


Prepare for deployment
----------------------
1. pip install -r requirements.txt
2. cd into the required site directory
3. hyde gen


Deploy
------
1. copy contents of [site]/build to a public http server


Make new site
-------------
1. pip install -r requirements.txt
2. cp -r [existing site] [new site]
