# Feed Reader Testing 

This project demonstrates unit tests using Jasmine. The project was made for Udacity Front-End program as a part of Google Developer Nanodegree Scholarship.

## Instruction

1. To run the application download or clone the repository from https://github.com/moniqka/feed-reader-testing.git
2. Right click on index.html and open it in your browser
3. The test results appears at the bottom of the page

(Tests are written in the Jasmine folder -> feedreader.js file)

## Tests

1. **RSS Feeds:**
	- tests if ```allFeeds``` variable has been defined and it is not empty
	- loops through each feed and ensures it has defined ```URL``` and it is not empty
	- loops through each feed and ensures it has defined ```name``` and it is not empty
2. **The menu:**
	- ensures the menu element is hidden by default
	- ensures the menu changes visibility when the menu icon is clicked
3. **Initial Entries:**
	- tests when ```loadFeed``` function is called and completes its work, if there is at least single ```.entry``` element within the ```.feed``` container
4. **New Feed Selection:**
	- tests when a new feed is loaded by the ```loadFeed``` funcion if the content actually changes
  
(Tests written with green font have passed and red have failed)
