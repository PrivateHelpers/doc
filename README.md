# Documentation: Data and Design
This is the *documentation* for the **"BitteSehr"** WebService,  the **"Gerne"** HelpersApp and the **"Danke"** RefugeeApp. This includes the resources "data" subdirectory and the "design" subdirectory for paper prototypes.


# Concepts

In the spirit of **Readme driven development** we start with READMEs first :)

## Overall Idea

The main overall idea is not only to help people forced to leave their country in war, but to enable them to help themselves (as far as possible) to master the necessary steps to get to their destination country, or to stay and live a self-determined life in Austria. The support of private  helpers and private initiatives is a further driving idea behind this project.

The aims:

* Support for refugees.
* support for private helpers, private initiatives.

The Target-groups:
	
* Refugees new to Austria.
* Refugees already for a longer time in Austria.
	
Personas:

* Peter fled Syria, because his house was bombed during the war and ... 

* Maria, an Afghan women, had to leave home without her family, afer ... 

Stories/UseCases:

* Peter is searching for German Courses to learn the language basics of German.
* Maria, who stays in private homes in Mureck, needs transportation to Graz, for visiting a Caritas help to help with translations for other refugees.

A friendly name for two apps and the backend:

* **DANKE**: *Danke* für die Zeit! *Danke* für das Geschenk! *Danke* für den Tipp!
* **GERNE**: *Gerne* helfe ich mit! *Gerne* unterstüzte ich Menschen in Not! *Gerne* überlasse jemandem ich Nützliches und Nötiges. 
* **BITTESEHR**: Hier sind die infos *bitte schön*!

	We came up with the names after short brainstorming for a *german*, *unique* word without umlauts, easy to remember, easy to find in stores and not hold by any company. Suggestions better names for the final deployed apps in the stores are welcome!

Features (Basic):

* BitteSehr Backend 
	* API to Add or modify information/data (including translations to several languages)
* Gerne HelpersApp
	* Update information and metadata (tags and categories for structure)
	* Send feedback to the developers (for bugs, improvements, suggestions)
	* Auto-Update of data
* Danke RefugeeApp
	* Select language
	* Find information (see Demo-Data) 
		* with links, email, tel to contact the service points
		* by categories
		* sorted  
	* Search (fulltext) in multiple languages
	* Share information with others (Facebook, Twiter, eMail)
	* Send feedback to the developers (for bugs, improvements, suggestions)
	* Auto-Update of data 
	
Features (Advanced):

* BitteSehr Backend 
	* manage push notifications for updates and/or news 
* Gerne HelpersApp
	* Create/Upload offer of free services, goods (including photos)
* Danke RefugeeApp
	* Mark and filter information
	* Register and login
	* Change settings in a personal "User Profile"
	* Offer help to others
	* Select goods you want to have for free

Features (Wishlist):
	
* Live Translations
* Routing

	
Demo Data:
 	Contacts (including image, tel. email, links)

## Information (in multiple languages)
The collection (and later the update) of reliable information is crutial. To make data searchable some meta data is helpful for full text search and search by tags and categories.

* Data for Info-Blocks
	* Title
	* Description
	* Image(s)
	* Tags
	* Contact(s)
		* Name (of organisation or person)
		* tel, email, address (zip, city, street)
		* routing-info (GPS)
		* url
		* opening hours
	* See also
	* Last update (of information)
	* Hints, Notes, Annotations

* Data for goods and services offered
	* Title
	* Description (for details: amount, size, language, color)
	* Location (where to pick up)
	* Last update (of information)
	* Hints, Notes, Annotations

* Data for goods and services searched
	* Title
	* Description (for details: amount, size, language, color)
	* Location (where needed)
	* Last update (of information)
	* Hints, Notes, Annotations

Find some [Demo Data](./DEMO-DATA.md) to get an idea of the different kind of information chunks.

## Plan: Step-by-Step Development

User Centred Design should involve the end users in early stage of development and focus on real live evaluation with the users.

**Phase I**, the design and internal development for core functionality. **Phase II**, implementation and deployment.

Phase I: 

 * Paper Prototpye of **"Danke"**, the Refugee App
 * Evaluation of Paper Prototpye
 * Code a first working prototype
 * Evaluation of Beta App (Betatesting)
 * Bugfixes

 * Paper Prototpye of **"Gerne"**, the HelpersApp
 * Evaluation of Paper Prototpye
 * Code a first working prototype
 * Evaluation of Beta App (Betatesting)
 * Bugfixes

 * Apps: Logo, Images, Iconsets
 * Apps: All text (system) in multiple translations

Phase II: (going public)

 * Add most basic features for **"Danke"**, the RefugeeApp 
 * Add most basic features for **"Gerne"**, the HelpersApp 
 * Add most basic features for **"BitteSehr"**, the ReST Web Service Backend
 * Deploment of Backend
 * Add real world data into the backend
 * Deployment of **"Danke"**, the RefugeeApp into Apple/Google App Stores
 * Deployment of **"Gerne"**, the HelpersApp into Apple/Google App Stores
 * Marketing

# Development

This section is meant for developers.

## Setup Infrastructure

Besides the cross platform development **Local Toolchain** for developers on a Unix/Linux machine with brew, npn, git, xcode, android, cordova, heroku and more some (demo) accounts have to be set up.

### Accounts

Done

* Accounts for the GIT repositories at GitHub
* Accounts for demo RoR hosting on Heroku

Todo:

* Accounts for Android, iOS Deployment 



# Outlook - Further steps

* Collect Data and translate into several languages
* Add Features such as PushNotifications


## See also

This is section [Documentation](https://github.com/PrivateHelpers/doc) is about **data**, **design** and **documentation**, as part of the [Private Helpers](https://github.com/PrivateHelpers/) initiative.

Sub Projects: ["Bitte Sehr" Web Service](https://github.com/PrivateHelpers/ws) is the name of a web service, implemented in RoR Ruby On Rails, a restful web service endpoint for the ["Danke" RefugeeApp](https://github.com/PrivateHelpers/refugeeapp) and the [HelpersApp "Gerne"](https://github.com/PrivateHelpers/helpersapp).



## Changelog
Initial Version from Dec 7, 2015.
