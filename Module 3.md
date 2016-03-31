### Fixing Data

#### What is XML and why should humanists care?
* structure of a written work conveys meaning as much as linguistic content
* ordered & hierarchical
* XML is structures model similar to a tree 
* root, contains everything else
* nodes, components & subcomponents of root
* humanities scholars use for two reasons:

1. human documents tend to translate well into XML b/c of ordered hierarchies
2. computers can operate quickly and efficiently on trees 

* first step in digital humanities: document analysis
* consider the documents you intend to use: identify useful hierarchical structure within them
* next, mark up/encode, make that hierarchy accessible to the computer 
* also called tagging in XML context
* otherwise computer won't know where to start and end its analysis/work
* digital humanities uses descriptive markup - describes what a textual subcomponent is
* presentational markup, describes what text looks like
* procedural markup, instructs computer on what to do to text 
* descriptive enables multipurpose use (only having to do markup once) where presentational and procedural do not
* one pitfall of XML is it doesn't cope well with multiple/simultaneous/overlapping hierarchies
* XML models using **elements**: consist of start tag, content and end tag
* tags written into text of XML documents, then read by XML-aware software
* end users typically don't see brackets

four types of content:

1. element content, only contains other elements
2. text content, contains only plain text
3. mixed content, mixture of plain text and other elements
4. empty element, no content

* **attributes** can also be added, for supplementary info on an element
* can be used to differentiate between differing elements of the same category, ie. French vs. German words both tagged as foreign
* written inside start tag, but not end tag 
* **serialization**, term for series of characters composing the tree 
* all elements must be nested properly - must close an element that was opened within another element
* when writing, helps to write start and end tags first, then fill with content
* this will guard against breaking the nesting/serializationvv   

###Exercises

####Exercise 1
* text encoding initiative
* transcribing a pamphlet into XML                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       
* **remember to upload XML & XSL files to repository on GitHub**