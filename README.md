# Protactor framework

* node-js
cross-platform that executed javascript code
* protactor
end-to-end testing framework for angularJS apps (spa)
*jasmine
BDD framework


installation - steps
---------------------

* Install NodeJs
* Install protactor
* install plugin for IDE

	
jasmine keywords
---------------------
https://jasmine.github.io/2.0/introduction.html
https://jasmine.github.io/pages/docs_home.html

File Structure
----------------
script.js:test suite
config.js: selenium address
		        specs location

Execute:
```
protactor config.js 
```

Reporting
---------
for reporting: 
	* install: protactor-beautiful-reporter
	* add to the config.js file

https://www.npmjs.com/package/protractor-beautiful-reporter

Non-Angular Applications
---------
https://github.com/angular/protractor/blob/master/docs/timeouts.md

Cross Browser Testing (by default is running in chrome)
---------
https://github.com/angular/protractor/blob/master/docs/browser-setup.md


headless mode

Need to configure the config.js file
	- chrome 60 and above
	- fireofox 55 and above


Database connection 
---------
https://www.youtube.com/watch?v=_JpjoenD5VA

More videos
---------
https://www.youtube.com/watch?v=XgmUkCISabc
