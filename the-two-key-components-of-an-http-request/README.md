# ![HTTP Request Response Cycle - The Two Key Components of an HTTP Request ](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will understand HTTP request syntax and URIs.

## The two key components of any HTTP request

Every HTTP request message begins with a request-line like this: 

```terminal
GET /puppies
```

1. The **HTTP method** (**GET** in the example above) is specified. 

2. The path/endpoint (**/puppies** in the example), also referred to as the URI.

> 🧠 A URI is not the same as a URL - A URI only identifies the requested resource, instead of specifying the full location as a URL would. For example, a URI of /puppies might correspond to a URL of https://awebsiteaboutdogs.com/puppies

These are considered the key components because most web frameworks use them to match routes defined on the server.