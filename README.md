# Code-Sight-for-Eclipse

This repository hosts the Code Sight plugin update site for Eclipse.

*Note*: The steps below should all be done as a single commit so that customers get the update immediately and are not left in a broken state without a valid 'update-site' directory

The URL to use is the 'raw' version so it serves up files in raw form from: 

> https://github.com/coverity/Code-Sight-for-Eclipse/raw/master/update-site


To update the update site in the future, move the current update-site to it's version with:

> % git mv update-site 2019.1.0


Then upload the new update site as 'update-site'
