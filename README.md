# Knowledge-Graph-Maker

## The following were used:

### OpenIE: https://github.com/dair-iitd/OpenIE-standalone/
When trying to run it their way I faced some issues when it came to installing it, so you need to install some of the files manually. Make sure to make a folder that will contain all the files. The "ListExtractor.jar" and "openie-assembly.jar" should be in that folder. Make a subfolder named "data" which will hold the "languageModel". After running a couple of tests those were the main ones that were needed to make the OpenIE to work. To use the commands refer to the link.  



### Neo4j: https://github.com/sem-onyalo/knowledge-graph-loader
For this one make sure to download the files uploaded to the this repo. Had to make some edits to the main.py due to some issues with the file searching. Make sure to make a temp .txt file and after making it use terminal to name it ".credentials". The username usually is just neo4j and the password depends on what you decide when making a local DBMS. Also have a folder named "data" which will hold the documents you're going to use as well as the "cache" folder. When switching to a different document make sure to delete cache to make it work. 
