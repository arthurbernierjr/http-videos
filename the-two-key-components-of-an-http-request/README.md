# ![HTTP Request Response Cycle - The Two Key Components of an HTTP Request](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will understand HTTP request syntax and URIs.

## The two key components of any HTTP request

Every HTTP request message begins with a request-line like this: 

```terminal
GET /puppies
```

A request-line consists of two key components:

1. The **HTTP method** (**GET** in the example above) is specified. This is kind of like an action that we want to perform. **GET** would retrieve information, but you have other methods for creating, update, and deleting.
2. The path/endpoint (**/puppies** in the example). This is kind of like the location of the resource upon which you are acting.

These are considered the key components because most web applications use them to determine what to do in response to a request.