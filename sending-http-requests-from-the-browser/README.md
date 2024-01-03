# ![HTTP Request-Response Cycle - Sending HTTP Requests From the Browser](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to identify and explain the various methods a browser uses to send HTTP requests, including the role a URL plays in navigating to requested resources. 

## Ways to send an HTTP request from the browser 

Browsers provide several ways to initiate HTTP requests, each suitable for different scenarios:

| Action                      | HTTP Method(s) | Details |
|-----------------------------|----------------|---------|
| Using the Address Bar       | GET            | When a URL is entered in the address bar, the browser sends a GET request to retrieve a web page or resource. |
| User Submits an HTML Form   | POST, GET      | POST is used for submissions that change server data (like account creation). GET is used for search forms, appending data in the URL as query parameters. |
| User Clicks a Link          | GET            | Clicking a link triggers a GET request to navigate to a new page or download a resource. |
| Using JavaScript            | Any            | JavaScript can use any HTTP method (GET, POST, PUT, DELETE, etc.) for dynamic requests, such as asynchronous data loading with `XMLHttpRequest` or `fetch` API. |



## URLs

URL stands for **Uniform Resource Locator** and is commonly known as a 'web address.' Its primary function is to identify and locate a resource, which aligns perfectly with the purpose of the **GET** method in HTTP — to retrieve or 'get' a resource.

> 🧠 Other methods like POST, PUT or DELETE require additional data beyond what a URL can safely provide, typically included in the request body, not the URL.


### Local URLs (http://localhost:3000/tacos)

**Description:** This is a basic URL often used for local development.

**Components:**
- **Protocol:** `http` - Indicates the use of the Hypertext Transfer Protocol.
- **Domain Name:** `localhost` - Refers to the local computer, specifically the one on which the development server is running.
- **Port:** `3000` - Specifies the port on which the server is listening. Developers can choose different ports to run different projects simultaneously.
- **Path:** `/tacos` - This specifies that we want to visit a page in our local project called `tacos`. If we haven't built such a page yet, our server will send back the classic message `page not found`.

**Usage:** Commonly used by developers when building and testing web applications on their own machines. It does not involve the internet, but rather the server runs locally on the developer's computer.

![URL Anatomy Example One](./assets/url-anatomy-a.png)


### Complex URLs with Query Parameters (https://developer.mozilla.org/search?q=reduce):

**Description:** This URL is typically used for specific and dynamic requests on the internet.

**Components:**
- **Protocol:** `https` - Signifies a secure, encrypted connection.
- **Domain Name and TLD:** `developer.mozilla.org` - Represents the internet address of the website or server.
- **Path:** `/search` - Identifies a specific resource or page, in this case, the search page on the website.
- **Query Parameters:** `?q=reduce` - Sends additional information to the server. Here, `q=reduce` indicates a search query for the term "reduce".

**Usage:** This URL structure is common for interacting with online resources. The query parameters, in this case, are used for search functionality, enabling users to find specific information on the website.

![URL Anatomy Example Two](./assets/url-anatomy-b.png)


