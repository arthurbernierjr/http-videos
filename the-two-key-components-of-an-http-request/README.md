# ![HTTP Request Response Cycle - The Two Key Components of an HTTP Request](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will understand HTTP request syntax and URIs.

## The two key components of any HTTP request

Every HTTP request message begins with a request-line like this: 

```terminal
GET /puppies
```

The request-line consists of two key components:

1. The **HTTP method**: This indicates the action we wish to perform. A **GET** method is specified in the example above. While a **GET** method would retrieve information,there are other methods for creating, update, and deleting information.

2. The path/endpoint (**/puppies** in the example). The path/endpoint identifies the location of the resource upon which you are acting.

These are considered the key components because most web applications use them to determine what to do in response to a request.