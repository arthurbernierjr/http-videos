# ![HTTP Request-Response Cycle - Fundamentals](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to explain the HTTP request-response cycle in detail, including understanding the roles and actions of both the client and server at each stage.

![HTTP Request-Response Cycle](./assets/req-res-cycle.png)

The **HTTP request-response cycle** refers to the process where a client sends an *HTTP request* and the server subsequently issues an *HTTP response* to that request.

This process is like a conversation. You ask (make a request), and then you get an answer (the response). Each request-response is a complete exchange, and a new one starts for every new action you take.

> 📚 An *HTTP request* is a message sent by a client to a server, asking for specific resources or actions. An *HTTP response* is the message a server sends back to the client as a reply to an HTTP request.

## Understanding the request-response cycle

Now let's take a deeper look into each stage of this process:

![HTTP Request-Response Cycle Steps](./assets/req-res-steps.png)

1. User Interaction with Client Software:
    - When you click a link, submit a form, or enter a URL, your web browser prepares to send a request to a server
    - Think of each action you take as a specific request. For example, entering a URL is like asking for a particular webpage
2. Client Software Processes Interaction: 
    - Your browser turns your action into an HTTP request. This includes choosing the right method (like GET or POST), the URL, and additional details like browser type.
    - Different actions (like clicking a link vs. submitting a form) use different types of requests. It's like choosing a different way to ask for something.
3. Server Software Processes the Request:
    - The server receives your request and figures out what to do. It might grab data, update something, or perform another task.
    - Servers can do a lot based on your request. When you ask for a webpage, the server finds all the pieces to put it together for you.
4. Server Returns a Response Message:
    - After the server does its work, it sends back a response. This includes a status code (like '200' for success) and often the data you asked for.
    - The status code is a quick way for the server to tell your browser how things went (success, error, or something else).
5. Client Processes the Response:
    - Your browser gets the response and acts on it. If it's a webpage, your browser shows it to you. If there's an error, it lets you know.
    - Your browser's job is to make sense of the server's response. Just like when you receive an answer, you react based on what you hear.


When the response is received by the client, that request-response cycle has ended and there will be no further HTTP communications unless another request is sent by the client.
