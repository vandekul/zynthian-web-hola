# Zynthian Web

This Website is built using Hola Skeleton as base template. 

Installation from scratch (PHP version 7.3.6+ required):

	`git clone -b master https://github.com/getgrav/grav.git	
	cd grav
	mv user user.bak
	git clone git@github.com:vandekul/zynthian-web-hola.git
	ln -s zynthian-web-hola/user .
	bin/grav install
	

Local run:

    	bin/grav server


## Engine page

Template: splash-engine

## Use-Case page

Template: splash-engine

In order to show engines section, after use-case content and before footer, you must check "Show Engines?" and inform "Tag for Engines".
The list of engines that will be shown must have the tag indicate in the second field (Tag for Engines).

![](/images/user-case-template.jpg)


