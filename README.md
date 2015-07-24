Add Snippet Alfred Workflow
========

Add new Alfred Snippet using

	## keyword: snippet

multi-line works  
keywords with spaces too

--



### Examples


	## apt up: apt-get update && apt-get upgrade 
	## html 5: <!DOCTYPE html>
	<html>
	<head>
	<title></title>
	</head>
	<body>
	
	</body>
	</html>


## Configuration
Click on the 'run script' part of the workflow (the middle bit) and read the two comments. You can change the location of the snippets database in case you've moved it. 

In case you forgot where:

	find ~ -name 'snippets.alfdb' (User Folder)
	find / -name 'snippets.alfdb' (Entire HD)

If this yields more than one result:

	find ~ -name 'snippets.alfdb' -exec stat {} \;
	

and use the last modified one.

Next you can change to the delimiter for the first two first fields. Note that this character can appear in the snippet itself, not a problem. It is colon by default but can be changed. Just click the middle item of the tier and change DLM to the desired character (surrounded by single quotes).