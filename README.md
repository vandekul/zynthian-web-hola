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


## Home page

### Use-Case section

Template: modular/usecase

It's possible to add more use cases from layout.  You must go to Hola Settings and add the information required for use-case.

![](/images/use-case-home-section.jpg)

## Engine page

Template: splash-engine

When you add an engine is important to choose the image that will be shown in the target and the image that will be in engine page:

![](/images/engine-images.jpg)

Also it's important to inform taxonomy:
- Category: it's used to filter in engines page
- Homepage: if indicates 'yes' it could be shown in a banner in engine's homepage section. This section only shows five engines randomly but this must have "category homepage = yes"
- Tag: this is used for engine's use-case section and also for filtering in engines page

![](/images/engine-taxonomy.jpg)

If you want to add media information like audios, videos or links, it's necessari to inform Media Setting section like here:

![](/images/engine-media.jpg)
![](/images/engine-page.jpg)

## Use-Case page

Template: splash-engine

In order to show engines section, after use-case content and before footer, you must check "Show Engines?" and inform "Tag for Engines".
The list of engines that will be shown must have the tag indicate in the second field (Tag for Engines).

![](/images/user-case-template.jpg)


