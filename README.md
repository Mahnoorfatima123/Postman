# Postman
# What is Postman?

#  - Main ideas
Postman is a tool that allows us to easily work with APIs.
Postman is used to build HTTP requests that we send to the server running the API.

# - How to install Postman
💡 - Main ideas
There are two ways to run Postman:
As a standalone app or

# Directly in the browser
The standalone app is available for Windows, macOS, and Linux.
Postman on the web works from any browser but you may need to download the Postman Desktop Agent if your requests fail.
DO NOT use the Google Chrome extension as this is deprecated and no longer updated.

# 📚 - Resources
Download Postman App
Open Postman on the web
Postman Desktop Agent (scroll down)

# Restful APIs
RESTful APIs (Representational State Transfer) play a crucial role in modern software development and are widely used for building web services. Understanding RESTful APIs and their significance in software testing is essential for ensuring the reliability and functionality of applications that rely on these APIs. Here's an overview:

# Understanding RESTful APIs:
Architecture:

REST is an architectural style that uses standard HTTP methods (GET, POST, PUT, DELETE) for communication between clients and servers.
It relies on stateless communication, meaning each request from a client to a server contains all the information needed to understand and fulfill the request.
Key Concepts:

# Resources: 
In REST, everything is a resource, and each resource is identified by a unique URI (Uniform Resource Identifier).
HTTP Methods: CRUD (Create, Read, Update, Delete) operations are performed using standard HTTP methods.
Representations: Resources can have different representations (JSON, XML, etc.) that clients and servers use to communicate.

# Statelessness:
RESTful APIs are designed to be stateless, meaning that each request from a client to a server is independent, and the server does not store any information about the client's state between requests.

#    - HTTP
# 💡 - Main ideas
The API we are using uses the HTTPS protocol.
HTTPS stands for Secure Hypertext Transfer Protocol.
HTTPS ensures that the connection is encrypted.
All APIs should use HTTPS.
From our point of view HTTP and HTTPS are the same.
The HTTP request message will contain:
URL (address)
Request method (GET, POST, PUT, ...)
Headers (User-Agent: Postman)
Body
The HTTP response message will contain:
Status code (200, 404, 500, ...)
Headers
Body
# Your first request with Postman
💡 - Main ideas
To use an API you need to read the API documentation. We're using Simple Books API whose documentation can be found in the resources section of this lesson below.
Work in Postman is organized in Workspaces.
A status code 200 (or any status like 2XX) indicates that the request was successful.
# 📚 - Resources

Simple Books API documentation
