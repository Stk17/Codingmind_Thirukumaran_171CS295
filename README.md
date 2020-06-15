# Codingmind_Thirukumaran_171CS295
-----------------------------------
TECHNICAL QUESTIONS
-------------------
# 1) What an API ? 
    
    An API is a software-to-software interface, not a user interface. With APIs, applications talk to each other without any user knowledge or intervention. When you buy movie tickets online and enter your credit card information, the movie ticket Web site uses an API to send your credit card information to a remote application that verifies whether your information is correct. 
 -------------------------------------------------------------------------------------------------- 
# 2) What is REST and which methods are there in REST ?
   
   REST is acronym for REpresentational State Transfer. It is architectural style for distributed hypermedia systems and was first presented by Roy Fielding in 2000 in his famous dissertation.
   
# HTTP GET
# HTTP POST
# HTTP PUT
# HTTP DELETE
# HTTP PATCH
 -------------------------------------------------------------------------------------------------- 
# 3) Which REST method will be cached in browser unless otherwise explicitly mentioned by
server ? 

POST APIs are used to create a new resource on server. So when you invoke the same POST request N times, you will have N new resources on the server. So, POST is not idempotent.

GET, HEAD, OPTIONS and TRACE methods NEVER change the resource state on server. They are purely for retrieving the resource representation or meta data at that point of time. So invoking multiple requests will not have any write operation on server, so GET, HEAD, OPTIONS and TRACE are idempotent.
----------------------------------------------------------------------------------------------------

# 4) Which REST method is idempotent and which method is not idempotent ? Explain with a small example
 
POST APIs are used to create a new resource on server. So when you invoke the same POST request N times, you will have N new resources on the server. So, POST is not idempotent.

GET, HEAD, OPTIONS and TRACE methods NEVER change the resource state on server. They are purely for retrieving the resource representation or meta data at that point of time. So invoking multiple requests will not have any write operation on server, so GET, HEAD, OPTIONS and TRACE are idempotent.

-----------------------------------------------------------------------------------------------------

# 5) Which REST method should be used to deal with user sensitive data like credit card
information etc. ?



-------------------------------------------------------------------------------------------------- 
# 6) What is the difference between http and https ? Explain shortly how https work

In HTTP, URL begins with “http://” whereas URL starts with “https://”
HTTP uses port number 80 for communication and HTTPS uses 443
HTTP is considered to be unsecure and HTTPS is secure
HTTP Works at Application Layer and HTTPS works at Transport Layer
In HTTP, Encryption is absent and Encryption is present in HTTPS as discussed above
HTTP does not require any certificates and HTTPS needs SSL Cert---------
In HTTP, Encryption is absent and Encryption is present in HTTPS as discussed above
HTTP does not require any certificates and HTTPS needs SSL Certificates

When you type any URL in the browser, the browser acts like a client & the website behaves like a server. The client uses HTTP protocol and fetches information from the server. The server returns an HTML page which the browser then renders and displays it to the user. 
--------------------------------------------------------------------
# 7) What is caching ? How does it help an application ?
  When we visit a new website frist time it takes longer to load but frequently accessed websites will load faster this is because the websites leaves some of its details and data in our system/browser, for example CSS. So that when it loads again it no need o load everything from web server only secured and main content alone will be loaded fro server reamaining details are loaded from client browser. So by this Caching  reduce the network traffic from the internet servers. it Reduces  latency and  Avoids network congestion.
-------------------------------------------------------------------------------------------------- 
# 8) What is the main difference between traditional relational databases and nosql databases ?

SQL databases follow ACID properties (Atomicity, Consistency, Isolation and Durability) whereas the NoSQL database follows the Brewers CAP theorem (Consistency, Availability and Partition tolerance).
When you type any URL in the browser, the browser acts like a client & the website behaves like a server. The client uses HTTP protocol and fetches information from the server. The server returns an HTML page which the browser then renders and displays it to the user.
 ----------------------------------------------------------------------------------------------------
# 9) Explain shortly MVC pattern in developing backend applications.
MVC pattern in developing backend applications.
MVC on the back-end”, with frameworks such as Spring MVC, means that the dynamic code and data makes MVC on the server,the view is rendered on the browser. MVC is implemented by full page refreshes as there is no dynamic code to do the redrawing on the browser.
 
-------------------------------------------------------------------------------------------------- --
# 10) What is event loop in javascript ? Explain with an example

Event loop basically is a result of event driven programming. Theoretically, event driven programming is application flow control that is based on events or change in state. In JavaScript, this is implemented using a central mechanism which listens for events and calls a callback function associated with it, whenever such event is triggered
--------------------------------------------------
# 11) Difference Between Git Fetch and Git Pull

Git fetch and Git pull are the two most important commands used in git repositories. Both the commands are used to download new data from a remote or cloud repository, but they  are not same in process."git fetch" is used to retrieve the latest changes made in the remote repository, it doesn’t merge those changes with your local repository.

Git pull also downloads the changes from the remote repository but also integrates them with the local repository. 
