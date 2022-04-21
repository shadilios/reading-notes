# Routing and Navigation Properties

![img](https://csharpcorner-mindcrackerinc.netdna-ssl.com/UploadFile/3d39b4/routing-in-mvc/Images/ASP.NET%20MVC%20Routing.jpg)

## Routing

Routing is connecting https requests to endpoints that the user will follow browsing a web application or a website.

<br><hr><br>
## Routing in MVC

* All ASP.NET MVC applications use ASP.NET routing by default.
* It's auto implemented inside the configuration file.
* A route table is created in the application's global.asax file.


<br><hr><br>
## Routing in Asp.NET core

* In Core, there's 2 functions that are responsible for Routing:
    1. UseRouting(): Adds a route matching the pipeline's middleware.
    2. UseEndpoints(): Adds endpoint to the pipeline's middleware.

* MapGet Method: is responsible for endpoints.
    1. Selecting endpoint by matching the URL with the HTTP method.
    2. Executing endpoint by running a delegate.


## URL generation

To seperate between endpoints and the URLS that access them, by creating a URL path based on a set of routes.

