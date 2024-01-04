# ![HTTP Request-Response Cycle - Anatomy of HTTP Request-Response Messages](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to describe the structure and components of HTTP request and response messages, including status codes, headers, and the message body in both requests and responses.

*HTTP messages* are how requests and responses are made between clients and servers. There are two types of messages, those making requests for information and those responding to those requests. Thankfully we as developers do not have to craft these by hand, that is done by the browser or server and follows a standard format.

Below is a diagram outlining the structures of both an HTTP request message and an HTTP response message:

![Request-Response Message Anatomy](./assets/http-req-res-msg-anatomy.png)

Notice they both have a *Start line* followed by *Headers*, an *Empty line*, and finally the *Body* of the message.

## Method and Path

Every HTTP request message begins with a start line like this: 

```terminal
GET /movies
```

This line will always include two essential components:

1. **HTTP Method:** Specifies the action to be performed. For example, **GET** in `GET /movies` is used for retrieving information.

2. **Path/Endpoint:** Indicates the resource's location, such as `/movies` in the example. This tells the server the location of the resource the request is targeting.

Without these two key components, a server does not have enough information to complete a request successfully. 

## HTTP Status Codes

In HTTP communication, every response message includes a *status code*, a three-digit number that indicates the result of a request-response transaction.

These codes fall into distinct categories, each representing a different type of response:

- **1xx** (Informational): These codes mean the server got the request and is still working on it.
- **2xx** (Success): This group shows that the request worked and was successfully processed.
- **3xx** (Redirection): These codes say that you need to do something else to finish the request, like go to a different web address.
- **4xx** (Client Error): This means there was a mistake on your end, like asking for something wrong or not having permission.
- **5xx** (Server Error): These codes tell you that the server couldn’t complete your request because it had a problem.

MDN maintains a full list of status codes with a summary of each [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status).

## Message Headers

HTTP headers are an essential part of HTTP requests and responses, acting as the messenger carrying additional information and instructions alongside the main content.

**Request Headers:**

  - These headers accompany an HTTP request. They provide context about the request, helping the server understand how to process it.
  - Common Headers: User-Agent, Accept, Host

**Response Headers:**

  - These headers are included in the HTTP response from the server. They give the client extra information about the response and how to handle it.
  - Common Headers: Content-Type, Set-Cookie, Cache-control


## Message body

The message **body** in HTTP is a key component of both requests and responses, carrying the actual data that needs to be communicated.

  - When a client sends a request to a server, the body of the message may include data necessary for that request. This is especially common in POST requests where the client sends data to the server (like form submissions). 
  - The response from the server often includes a body containing the requested data.

In the above example, the body of the request contains data, while the body of the response returns `HTML` to be displayed. Although the HTTP protocol is text-based, the content in the body can be binary - for example, images are typically transferred in a *binary format*.

> 📚 A *binary format* refers to data represented in binary code, consisting of only 1s and 0s.

