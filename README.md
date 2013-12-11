# madlib-all

This is a meta package that will include all the Marviq Application Development library modules. It exists purely as a convenience module to try everything in one go. For normal development you would more likely only npm install the modules you actually need.


## acknowledgements
The Marviq Application Development library (aka madLib) was developed by me when I was working at Marviq. They were cool enough to let me take the code with me when I decided to start my own company. We decided to open source it for our mutual benefit and we are still contributing to each others work.


## philosophy
JavaScript is the language of the web. Wouldn't it be nice if we could stop having to rewrite (most) of our code for all those web connected platforms running on JavaScript? That is what madLib hopes to achieve. The focus of madLib is to have the same old boring stuff&tm; ready made for multiple platforms. Write your core application logic once using modules and never worry about the basics stuff again. Basics including XHR, XML, JSON, host mappings, settings, storage, etcetera.

Currently madLib is focused on the following platforms:
* Web browsers (IE6+, Chrome, Firefox, Opera)
* Appcelerator/Titanium
* PhoneGap
* NodeJS


## installation
npm install madlib-all

All the madlib modules are declared as peer dependencies and will be installed alongside each other inside your node_modules folder.