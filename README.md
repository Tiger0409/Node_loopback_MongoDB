# Node_loopback_MongoDB
Loopback with Node.JS and MongoDB This post is a continuation of “Mean Stack App Sample — The backend (I)”, with the api from the previous post I will make some test with Loopbak 3.x

# *****Node Cash clear command.
https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/0_1.PNG

## 1) Select All files.
## 2) Delect All files.

# Let´s start.

You can build as following:

## 1). Create Nodejs_Loopback folder.
## 2). Open Command Prompt.
    
	Path:  Created folder
	
## 3). npm install npm --global

https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/IMG_git/1.PNG

## 4). npm install express
	

## 5). npm install
https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/IMG_git/2.PNG
## 6). npm install -g strongloop

https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/IMG_git/3.PNG

## 7). slc loopback todo

	Enter
	New Created folder name
	3.x
	empty-server (An empty LoopBack API, without any configured models or datasources)
https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/IMG_git/4.PNG

	
## 8). Created models

	Cd/ New Created folder name
	slc loopback:model
	https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/IMG_git/5.PNG
	
	 Enter the model name: cat
		 Select model's base class PersistedModel
		 Expose cat via the REST API? Yes
		 Custom plural form (used to build REST URL): cats
		 Common model or server only? common
		Let's add some cat properties now.

		Enter an empty property name when done.
		 Property name: name
		   invoke   loopback:property
		 Property type: string
		 Required? Yes
		 Default value[leave blank for none]:

		Let's add another cat property.
		Enter an empty property name when done.
		 Property name: weight
		   invoke   loopback:property
		 Property type: number
		 Required? Yes
		 Default value[leave blank for none]:

		Let's add another cat property.
		Enter an empty property name when done.
		 Property name: age
		   invoke   loopback:property
		 Property type: number
		 Required? Yes
		 Default value[leave blank for none]:

		Let's add another cat property.
		Enter an empty property name when done.
		 Property name:
		
		...    
https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/IMG_git/6.PNG
		
		
## 9). Install

	node .
	
	Web server listening at: http://localhost:3000
	Browse your REST API at http://localhost:3000/explorer
	
https://github.com/Tiger0409/Node_loopback_MongoDB/blob/master/IMG_git/1.PNG
	
## 10. Test:
