###Ian Milligan presentation:

* pitfalls of digitized historical data: requires institutional support/$, so often replicates holdings of elite, Western institutions
* different ways to get data: The Dream Case, scraping data yourself with free software, API's, Wget

###Milligan's "Illusionary Order: Cautionary Notes for Online Newspapers"

* dangers of digitized newspapers, can skew research
* "using Pages of the Past uncritically for historical research is akin to using a volume of the Canadian Historical Review with 10% or so of the pages ripped out"
* optical character recognition (OCR) - conversion of scanned words to readable text, leaves potential to miss words from scanned microfilm
* can miss pieces of articles continued from previous pages by chance because of placement of headline/keywords
* Toronto Star & Globe and Mail digitized by private companies - why is this potentially problematic?
* How do the tools we're using shape our research?

###Exercise 1: The Dream Case

* data sorted into pre-existing database, compilers should have laid out their methodologies & decision making process
* Searched Commonwealth War Graves Commission database for war dead> surname: Racine
* Results saved in downloads as excel spreadsheet, look for CasualtySearch

###Exercise 2: Outwit Hub

* Downloaded free trial of OutwitHub
* Software that allows you to scrape the HTML of a website
* Ran exercise as per instructions in notebook, results can be found in Documents folder

* Really confusing as to what exactly this is doing, but it did come up with some cool data
* Brought up information on the use of "pie" and different meanings
To do in Mod 2. reflection: Write this exercise up in your notebook. What other data does outwit include with your export? How might that data be useful?

###Exercise 3: APIs

* application programming interface, allows your computer to talk to host site's computer so it will share data with you
* simplified explanation: your computer puts in the search terms rather than you - means they generally come back in a machine-readable format 
* ie. JSON format
* Search ottawa, date range 1900 to 1900 on Canadiana Discovery Portal
* search query can be seen by looking at the URL: http://search.canadiana.ca/search?q=ottawa&field=&df=1800&dt=1900
* Everything after "/search" is a command you are sending to the Canadiana server
* Guide to API commands [here](http://search.canadiana.ca/support/api)