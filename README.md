Solution Description:
	Please refer" FE Technical Test.docx"

Technologies used
.Angular
.Bootstrap
.Jasmine
.Karma
.Grunt

How to Run Application

	1. Download the application at a particular folder on your machine
	2. Mark Root directory as Application in IISManager
	3. Browse  http://localhost/VDirName/app/view/progressBar.html

How to Run Unit Tests

Prerequisite (Node.Js is installed on the machine)

	1. run npm install to load node modules
	2. Once this is done run following Grunt command on root
		A. grunt Karma OR Grunt  	==> to run Jasmine tests
		B. grunt minify			==> to minify CSS and JS


Following functionalities achieved (description from ' FE Technical Test.docx')

Feature overview:

	1. Multiple bars			==>	Yes

	2. One set of controls that 
	can control each bar on the fly 	==> Yes

	3. Can't go under 0 			==> Yes

	4. Can go over 100			==> Yes

	5. but limit the bar itself and 	==> Yes
	change its colour Display 
	usage amount centered

	6. Consider animating the 		==> Yes
	bar change Consider linear gradient 
	for the bar 

	7. Consider a responsive 		==> Yes
	solution:

 	8. testing it on mobile, tablet, 	==>	Yes
 	etc.Getting it working nicely.


Following enhancements could have been done

	1. Split Gruntfile.js into individual config files(grunt-config-factory)

	2. Ship IISExpress to solution and run application with it

	3. Use SAAS

	4. Template caching

	5. Suggestions welcome :)
	
