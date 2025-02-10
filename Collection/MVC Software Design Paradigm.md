
# MVC Lecture.


## What is MVC?*

MVC stands for Model,View,Controller, a software design paradigm that allows us to organize our code more efficiently by breaking it into three parts (Model,View, Controller).
By breaking our code into different sections, we can have greater control over those sections and parts of our code without impacting the overall application.

## What does the Model represent? 

The Model represents the database. It contains all of the data within the application but with no connection to the user. The function of the model is to interact with and perform database-related tasks separately from dealing with user interface. It also can define the most important components of your application. The model does not depend on the controller or the view.

## What does the View represent?

The View represents the client/user and how the user views that data. 
Since View is the User Interface of which customers can performs some actions, It contains HTML

## What does the Controller represent?

The Controller represents the API/Behavior which interacts with the client and database and controls how the two interact with each other.A huge part is managing data requests from the server and rendering it out on the views without the other two contacting each other.

## Who created MVC and Why?

MVC was created by Trygve Reenskaug in the late 1970s because he wanted a software design pattern that could help users interact with a large data sets. By splitting 


A user triggers a request which travels to a endpoint which triggers a controller that has code instructs about further action. 

**

Advantages to MVC:
	1. Code Maintainability
	2. Complexity Reduction
	3. Able to test different components without affecting the entire application
	4. 

Disadvantages to MVC
	 1. Not for small applications.
![[mvc.png]]

#SWE 
#javascript 