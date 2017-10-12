# Code-Task

Details of Number printer project 
1.	Introduction
The developed solution will address the given Task with following criteria

•	A web service – Web API service 
•	Frontend JavaScript application – Knockout.js based JavaScript client 
             To fulfill the given hint and to highlight the good framework for developing extensible, loosely coupled, maintainable and testable web application this solution has been designed with N-Tier architecture and DI and Repository Pattern.
              1.1 Technologies Used 
               Web API, MVC 5, Knockout.js, Autofac, AutoMapper, FluentValidation, NUnit, Moq

1.2	Source Code Organization

 
o	NumberPrinter.Core
Contains core and general classes or interfaces that will be shared across the layers, such as domain entities/business objects, helper/util classes.

o	NumberPrinter.Repository
Contains the repository interfaces and implementation of repository interfaces. This project should not be used directly by any other projects in the solution. Instead, the implementation of repository should be consumed via Dependency Injection using AutoFac.

o	NumberPrinter.Services
Contains a set of core services, business logics and validations. Also known as Business Logics   Layer.

o	NumberPrinter.Web
Contains both WebApi( http://localhost:51225/api/cheque) and Knockout.js based WebApi client.
o	NumberPrinter.Web.Tests
Contains Unit tests for Controller and services.

                  
2.	Overview of technologies used.

1)	Frontend JavaScript client
Knockout.Js (NumberPrinter.Web/ Scripts/ app.js
                      Frontend Validation – HTML 5 Validations
2)	WebAPI Presentation layer
FluentValidation – Model.State validation
AutoMapper – Map the Viewmodel to Model 
Autofac – For DI registration and as IOC container

3)	Unit Testing
NUnit
Moq
