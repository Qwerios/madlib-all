# madlib-all
This is a meta package that will include all the Marviq Application Development library modules. It exists purely as a convenience module to try everything in one go. For normal development you would more likely only npm install the modules you actually need.


## acknowledgments
The Marviq Application Development library (aka madLib) was developed by me when I was working at Marviq. They were cool enough to let me publish it using my personal github account instead of the company account. We decided to open source it for our mutual benefit and to ensure future updates should I decide to leave the company.


## philosophy
JavaScript is the language of the web. Wouldn't it be nice if we could stop having to rewrite (most) of our code for all those web connected platforms running on JavaScript? That is what madLib hopes to achieve. The focus of madLib is to have the same old boring stuff ready made for multiple platforms. Write your core application logic once using modules and never worry about the basics stuff again. Basics including XHR, XML, JSON, host mappings, settings, storage, etcetera.

Currently madLib is focused on the following platforms:
+   Web browsers (IE6+, Chrome, Firefox, Opera)
+   Appcelerator/Titanium
+   PhoneGap
+   NodeJS


## installation
npm install madlib-all

All the madLib modules are declared as peer dependencies and will be installed alongside each other inside your node_modules folder.