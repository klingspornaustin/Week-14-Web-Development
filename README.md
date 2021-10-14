# Week-14-Web-Development

What type of architecture does the HTTP request and response process occur in?
**Client-Server Architecture**

What are the different parts of an HTTP request?
**Request line, headers, whitespace**

Which part of an HTTP request is optional?
**Body**

What are the three parts of an HTTP response?
**Status line, response header, body**

Which number class of status codes represents errors?
**400s and 500s**


What are the two most common request methods that a security professional will encounter?
**GET and POST**

Which type of HTTP request method is used for sending data?
**Post**

Which part of an HTTP request contains the data being sent to the server?
**Request line**

In which part of an HTTP response does the browser receive the web code to generate and style a web page?
**When the server receives the request, it sends back an HTTP response stating if the HTTP 200 is OK**


## Using curl

What are the advantages of using curl over the browser?
**The ability to verify familar servers**

Which curl option is used to change the request method?
**-X**

Which curl option is used to set request headers?
**-H**

Which curl option is used to view the response header?
**-I**

Which request method might an attacker use to figure out which HTTP requests an HTTP server will accept?
**GET because then that would confirm if the server is reachable or not**


## Sessions and Cookies

Which response header sends a cookie to the client?
**Set-Cookie**

Which request header will continue the client's session?
**Cookie**

What is the request method?
**Post**

Which header expresses the client's preference for an encrypted response?
**Upgrade-Insecure-Requests**

Does the request have a user session associated with it?
**I don't think so but it does say something about a connection so not sure. But I would say no.

What kind of data is being sent from this request body?
**Login username and password**

What is the response status code?
**200 OK so good**

What web server is handling this HTTP response?
**Apache**

Does this response have a user session associated to it?
**Yes its number 5**

What kind of content is likely to be in the [page content] response body?
**Words and text**

If your class covered security headers, what security request headers have been included?
**Strict-Transport-Security**


## Monoliths and Microservices

What are the individual components of microservices called?
**Front-End-Server, Back-End-Server, Database**

What is a service that writes to a database and communicates to other services?
**Back-End-Server**

What type of underlying technology allows for microservices to become scalable and have redundancy?
**Having containers on a system**


## Deploying and Testing a Container Set

What tool can be used to deploy multiple containers at once?
**Docker**

What kind of file format is required for us to deploy a container set?
**YAML or .yml**

## Databases


Which type of SQL query would we use to see all of the information within a table called customers?
**Select**

Which type of SQL query would we use to enter new data into a table? (You don't need a full query, just the first part of the statement.)
**INSERT INTO**

Why would we never run DELETE FROM <table-name>; by itself?
 **You don't want to delete the whole table if you make a mistake**
