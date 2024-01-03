# ![HTTP Request-Response Cycle - Level Up - Additional HTTP Methods](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will get an overview of all of the available HTTP methods.

## Additional HTTP methods

There dozens of additional HTTP methods that you will likely encounter in your career. It is helpful to be aware of the most common HTTP methods and to understand how they can be used. See this documentation from [Mozilla's developer network](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods) that explains the 9 most common HTTP methods. 

| HTTP Method | Description                                  |
|-------------|----------------------------------------------|
| `GET`       | Retrieves data from the server.              |
| `POST`      | Submits data to the server to create a new resource. |
| `PUT`       | Updates existing data on the server.         |
| `DELETE`    | Removes data from the server.                |
| `HEAD`      | Similar to GET, but only retrieves the headers (not the body of the resource). |
| `CONNECT`   | Establishes a tunnel to the server.          |
| `OPTIONS`   | Describes communication options for the target resource. |
| `TRACE`     | Performs a message loop-back test along the path to the target resource. |
| `PATCH`     | Applies partial modifications to a resource. |


If you choose to dig deeper and investigate the HTTP protocol specifics, you'll see that there are about [39 different HTTP methods in HTTP1.1](http://www.iana.org/assignments/http-methods/http-methods.xhtml).

Even if an HTTP method is included in the protocol spec, that doesn't mean that all HTTP clients will support all of these methods, you most likely will not encounter the majority these verbs in your career, but it is helpful to understand how these protocols are designed and utilized.