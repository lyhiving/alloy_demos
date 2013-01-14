themes
======

This app shows how you can use Alloy's theming functionality to quickly, and non-invasively change the appearance and layout of your app. This is appealing from the pure perspective of external styling, but it is also a very powerful tool when it comes to branding your app for multiples companies/experiences. When showing this demo I generally highlight the following:

* The fact that themes are located in the **app/themes** folder and are organized by name
* Each theme can have both an assets and styles folder. This allows not just for styling, but making assets theme-specific will also reduce the overall size of your deployed application.
* There's no limit to the number of themes
* The ease with which a theme can be changed
* Themes can be applied by the platform and/or deployment type in the **app/config.json** file. The config.json in this project shows different themes being applied based on platform.

Requirements
------------

* Titanium SDK 3.0.0.GA
* Alloy 0.3.4
* Platforms: iOS, Android. Mobileweb supports themes, but this demo is not optimized for it.
