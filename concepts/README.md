# ![HTTP Request-Response Cycle - Concepts](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to explain the concept of HTTP (Hypertext Transfer Protocol).

## What is HTTP?

[HTTP (Hypertext Transfer Protocol)](https://developer.mozilla.org/en-US/docs/Web/HTTP) is a set of rules that applications follow when communicating with each other over the internet. These rules help to ensure client and server applications can reliably communicate with one another.

Imagine visiting a restaurant. When you enter and sit down, you are presented with a menu. The waitperson then asks for your order, giving you time to choose. After you make a selection, they relay the order to the kitchen and bring your meal when it is ready. This sequence is a *protocol* - a set of established rules for dining in a restaurant. If you tried to order directly from the chef or were brought random dishes without requesting them, the system would become confusing and chaotic.

Similarly, applications use the HTTP protocol to request and receive services provided by servers over the internet. This protocol ensures a smooth and orderly transfer of data, just like the rules in a restaurant guide the reliable order and delivery of your meal.

In a traditional web application, when you visit a website, you can browse and then take an action (such as clicking on a link). Using the HTTP protocol, your browser relays this request to a web server, which prepares and responds with a new HTML page. When your browser receives it, it is rendered in the browser window for you to see and interact with. The cycle can repeat - it is carried out on every request you make in the browser.

![HTTP Request-Response Cycle](./assets/req-res-cycle.png)

To draw a parallel with our restaurant analogy, consider your interactions with the restaurant's waitstaff as the "protocol" allowing you (the client) to interact with the kitchen (the server), which is there to prepare food in response to your orders or requests. Just as the waitstaff in the restaurant prepares your order request for the kitchen and brings you the resulting prepared meal, the browser prepares your HTTP request and shows you the results of that request.
