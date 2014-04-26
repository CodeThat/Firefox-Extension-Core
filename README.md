Firefox-Extension-Core
======================

Files to create a firefox extension framework quickly

Files description:

- install.rdf (XML for extension details, version min-max, extension ID, author, homepage)
- /chrome/content (contents of the extension, XUL, skins, JavaScript)
- chrome.manifest (specifies material in chrome package, name of chrome package, and location of chrome package files) 
- core.xpi (zipped up core files, can install naturally to Firefox)

*During extension development a text file will still need to be added to ~.mozilla/extensions/ named as the ID in email format and containing the full path to the firefox extension directory. Otherwise Firefox will not know the extension exist. You can also just install the core.xpi.


