date: 2013-01-22
author: Morten Bo Nielsen
email: mon@eal.dk

Course manager
--------------

This is basically a python script using [flask](http://flask.pocoo.org/), templates and [markdown](http://daringfireball.net/projects/markdown/basics) files to enable autogeneration of course descriptions and cross linking them.

This is the first attempt, but it has its uses :-)

* Course descriptions are found [here](/Plask/fagplan/)
* Cross course overview are found [here](/Plask/overview/index.html)

In the overview select the exam questions. It should be a good example why this structure is useful.


Data structure
--------------

Each course has multiple files

* 01_Introduction.md - general description of the course
* 02_Teaching gaols.md - Desciption of teaching goals
* 03_Learning goals.md - Student readable and measurable learning goals.
* 04_Evaluation.md - An overview of hand-ins and a description of how to get the course approved
* 05_Literature.md - The description of books or other resources used in the course
* schedule.csv - The weekly schedule. This is a csv file, using tab as delimiter. The columns: 
	* Week - the week number
	* Lessons - The number of lessons in the course on a given week
	* Topic	- the topic(s) of the weeks
	* Comments - comments like hand-ins and the like

Also, all this is maintained in a local git repo, and the sources should be available [here](/PlaskSrc/).

Please note: this is work-in-progress.
