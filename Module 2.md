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

**To do in Mod 2. reflection: Write this exercise up in your notebook. What other data does outwit include with your export? How might that data be useful?**
* Really confusing as to what exactly this is doing, but it did come up with some cool data
* Brought up information on the use of "pie" and different meanings


###Exercise 3: APIs

* application programming interface, allows your computer to talk to host site's computer so it will share data with you
* simplified explanation: your computer puts in the search terms rather than you - means they generally come back in a machine-readable format 
* ie. JSON format
* Search ottawa, date range 1900 to 1900 on Canadiana Discovery Portal
* search query can be seen by looking at the URL: http://search.canadiana.ca/search?q=ottawa&field=&df=1800&dt=1900
* Everything after "/search" is a command you are sending to the Canadiana server
* Guide to API commands [here](http://search.canadiana.ca/support/api)
* Add "&fmt=json" to the end of URL to translate to JSON
* Each individual item in the new JSON list of our search has an oocihm number attached to it: how do we retrieve these?

* Wget is a useful program, run through your computer’s command line, for retrieving online material
* Saves time, alternative to right clicking and saving everything individually
* Enables you to download either an entire site or entire section of a site that falls under a certain section of its menu hierarchy
* Homebrew: package manager software, runs through Terminal
* http://brew.sh/
* Runs using Ruby language?
* JQ: helper program that reads .json data

Here, Dr. Graham advised me to skip it (I didn't leave myself enough time). :(

###Exercise 4: Tracking the ephemeral web

* Data on the web can be outdated within a matter of hours
* http://www.anonymousswisscollector.com/2015/10/saving-info-and-your-skin-on-the-ephemeral-internet-a-how-to-for-researchers.html
* Sometimes, data/info on the web will disappear
* Critical for researchers to archive it to save their work & reputations
* Wayback bookmarklet, allows you to save current version and access any previous versions of a given page
* Can also give access to older versions of a page if it comes back as a 404
* Access these at archive.org
* BibDesk, allows to save & organize PDF's of academic articles
* Also, print & back up your files
* Problem: sites can simply include robot.txt in the code of their sites and Wayback will automatically omit it from its records

Following steps found [here][http://blog.archive.org/2012/04/26/downloading-in-bulk-using-wget/] to save search results using wget
* Use archive.org to identify a search query

*Can also archive Twitter to JSON using [this][https://github.com/shawngraham/twarc]
 