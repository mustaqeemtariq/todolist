
## What is Web API?
1. Web API is a technology that consists of two main parts: the "Web" part and the "API" part.

2. Web Part: The "Web" part refers to the means of exchanging information over the internet, commonly using the HTTP protocol or web browsers.

3. API Part: The "API" part, which stands for Application Programming Interface, is a collection of operations or functions that you can invoke on a machine, either locally or remotely, to interact with and access specific functionality.

Web APIs enable developers to access and utilize the operations they provide to enhance the functionality of their applications.

Examples of Web APIs:
Here are a few examples of Web APIs:

**Microsoft Graph**: Microsoft Graph is a Web API that provides a unified programmatic interface to access data and services from Microsoft 365, Windows 10, and other Microsoft cloud services. Developers can use it to integrate Microsoft services into their applications.

**Azure DevOps**: Azure DevOps offers a set of Web APIs that allow developers to interact with various aspects of the Azure DevOps platform. These APIs can be used to automate processes, manage projects, and access project-related data.

---

## What is HTTP?
HTTP, which stands for Hypertext Transfer Protocol, is a fundamental protocol used to facilitate the exchange of information between different systems over the internet. It plays a crucial role in enabling communication between computers and devices, even if they are located in different parts of the world.

HTTP is an open standard and is defined in a document called RFC 2616, which outlines the protocol's specifications and guidelines. It is the backbone of the World Wide Web, powering the transfer of text, images, videos, and other types of data.

Request Structure:
When making an HTTP request, it typically consists of the following components:

- Request Line: This part specifies the HTTP method (e.g., GET, POST), the resource or URL being accessed, and the version of HTTP being used.
- Headers: Headers contain additional information about the request, such as the user agent, accepted content types, and cookies.
- Body: The request body (optional) can contain data sent to the server, often used for operations like posting form data or sending JSON payloads.
Response Structure:
When an HTTP request is processed, the response from the server follows a structured format:

- Status Line: The status line contains information about the outcome of the request, including the HTTP status code (e.g., 200 for a successful request) and a status message.
- Headers: Similar to request headers, response headers provide additional information about the response, such as the content type and server information.
- Body: The response body carries the requested data or content, which can be HTML, JSON, XML, or other formats, depending on the nature of the request.
HTTP is a key technology that enables the worldwide exchange of information and plays a central role in the functionality of websites and web applications.

---

## What are controllers and action methods?
Within the context of **ASP.NET Core**, the job of controller is to be able to receive requests that get sent over that match a particular path. The controller will have various operations that will inspect the requests, carry out any necessary business logic and then return a response to the client. These operations are usually called **Action Methods**.

---

## What is Swagger UI?
Swagger is a collection of open source tools that make it easier for developers to build and consume api. Some of those tools include
- Client generation
- Api documentation
- Api debugging 
Swagger relies on OpenAPI Specification that allows us to define some of the detailed things that API are able to do.

Swagger support in ASP.NET Core can be enabled by installing a git package called **Swashbuckle**.

---

## What are Records?
Records are almost exactly like classes except that they have some additional benefits. It provides support for immutability and equality