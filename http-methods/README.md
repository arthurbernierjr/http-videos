# ![HTTP Request-Response Cycle - HTTP Methods](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to identify and explain the four primary HTTP methods: GET, POST, PUT, and DELETE.

## HTTP Methods

[HTTP methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods) are used to indicate the desired action to be performed on a given resource on the server.

| HTTP method | Desired action on the server |
| ----------- | ---------------------------- |
| `GET`    | Requests a specific resource from the server. Only used for retrieving data. |
| `POST`   | Sends data to the server to create a new resource.                           |
| `PUT`    | Sends data to the server to update an existing resource.                     |
| `DELETE` | Requests the removal of a specified resource from the server.                |

## Use Cases

Here are some real scenarios to see these methods in action:

A user wants to view the latest news articles on a news website.

- The user navigates to the news website and clicks on the "Latest News" section. The browser sends a **GET** request to the server to retrieve and display the latest news articles.

A user is creating a new profile on a social media platform.

- The user fills out a sign-up form with their details and clicks 'Submit'. This action sends a **POST** request to the server, instructing it to create a new user profile with the provided information.

A user is updating their profile picture on a social media account.

- The user selects a new profile picture and confirms the update. The browser sends a **PUT** request to the server, instructing it to replace the existing profile picture with the new one.

A user decides to delete a blog post they have written on a blogging platform.

- The user navigates to their blog post and clicks the 'Delete' button. The browser sends a **DELETE** request to the server, instructing it to remove that specific blog post.

## 🎓 You do

**Scenario 1:** A user is checking their current balance on an online banking website.

1. Identify the HTTP method used when the user views their account balance without making any changes.

**Scenario 2:** On an e-commerce website, a user adds a new shipping address to their account.

2. Identify the HTTP method used to add this new information to the user's account details.
