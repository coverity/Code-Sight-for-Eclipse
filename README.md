# Code-Sight-for-Eclipse

This repository hosts the Code Sight plugin update site for Eclipse.

*Note*: The steps below should all be done as a single commit so that customers get the update immediately and are not left in a broken state without a valid 'update-site' directory

The URL to use is the 'raw' version so it serves up files in raw form from: 

> https://github.com/coverity/Code-Sight-for-Eclipse/raw/master/update-site

To update the update site in the future, rm the current update-site and replace it with a new version:

> % git rm -r update-site


Then upload the new update site directory as 'update-site'

Create a release on GitHub for this new version of Code Sight for Eclipse: 
https://help.github.com/en/articles/creating-releases 
