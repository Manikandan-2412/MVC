# MVC

                                       MVC
                   MVC Framework                   MVC Core                
-----------------------------------------------------------------------------------

         .Net Framework                             .NET Core
         =============================================================
         development can happen                       cross platform
         only in windows

         asp.net                                      mvc core

         Not open source                              open source(git hub)

         CLR                                          Core CLR

         FCL                                          CoreFX

         minimum support for command                  full support for command
         csc                                          dotnet   

         no support for blazor,                       supports all
         no support for microservices
         not much support for cloud
         no support for docker


         not modular                                 modular in nature

         supports asp.net                           no asp.net
         supports windows app                       no support

         mf,df,cf                                   df,cf


         ado.net                                    no ado.net
===============================================================================
         

---------------------------------------------------------------------------------------
dotnet commands:
---------------
1. dotnet --version 
2. dotnet help
3. dotnet new -l:
4. dotnet new console 
5. dotnet new mvc
6. dotnet new classlib
7. dotnet build
8. dotnet run
9. dotnet add reference ../foldername/projectname
10. dotnet add package (Newtonsoft.Json)Package name
==========================================================================================
intro:
----
light weight framework for building web application 
no concept of page life cycle


drawbacks:
---------
RAD may not be possible
Required highly skilled developers


Asp.Net features:
-----

RAD 
built in validation controls
built in navigations controls & login 
built in controls to interact with database
easy to use like Ad rotator,tree view,etc
good for non.net programmer

Drawbacks for Asp.Net:
-----------
page size is heavy
it not suitable for mobile
server side code is difficult to integrate with Html
page life cycle creates complexities
Difficult to test the application 

Common Features:
----
Master page
data bindng
session
form authentication
output and data caching 
configuration system.


=========================================================
MVC:
----
Model View Controller (MVC) :
architectural pattern separates an appliction into three main components
the mvc framework is define in the Microsoft.Asp.NetCore.Mvc namespace

Model: Represents data
View : User Interface 
Controller: Handles User request



Razor syntax is always given in the view class.


Passing Data from Controller to View:
-----------------------------------
We have three options to pass data from controller to view in asp.net mvc application those are 
  view data
  ViewBag
  TempData
  --------------------------------------------
View Data:
-------
view data is used to pass data from controller to view and it contains null when the direction occurs
only used belongs to that page

ViewBag:
--------
the viewbag is a dynamic type property
it doesn;t need type casting 

TempData:
-------
it is a object type
we can able to used many pages
Keep is used for that

Action Selectors:
---------------
any method is created in the controller is called action method

Action Name --> alias for the method
Non Action  --> blocking of a method
Action Verb --> HttpGet and HttpPost


