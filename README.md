# 📝 Posts List App

Welcome to the Media App project! This repository is designed for students to practice their React skills by building a functional  application. The tasks are divided into three levels: Basic, Medium, and Hard. Each level introduces new concepts and challenges to enhance your understanding of React.

### Links
1. https://www.figma.com/design/7oTkQsdn1fl6sYB2b9hKNd/nFactorial-Web-Course?node-id=9-578&t=jHQoUmCnN3Kfuh8S-0
2. https://medium.com
3. https://dummyjson.com/docs

## 📚 Table of Contents

- [Getting Started](#getting-started)
- [Basic Level](#basic-level)
- [Medium Level](#medium-level)
- [Hard Level](#hard-level)


## 🚀 Getting Started

To get started with this project, follow these steps:

1. Fork this repository to your GitHub account.
2. Clone the repository to your local machine:
   git clone https://github.com/your-username/todo-list-app.git
    3. Install dependencies:
       cd todo-list-app
       npm install
    4. Start the development server:
       npm run dev


## 🥇 Basic Level

In the Basic level, you will implement the core interface of application.

### Tasks
- [ ] Fetch all posts using axios
- [ ] Implement posts design on main page.
- [ ] Implement routing to detailed post page using dynamic routes.

## 🥈 Medium Level

### Tasks
- [ ] Create AuthContext that checks if the user is authenticated. If the user is not authenticated, they will be redirected to the login page.
- [ ] Create Login Page that sends request to 'https://dummyjson.com/auth/login' in order to get auth token.
- [ ] Rewrite all your axios requests by passing auth token (check Authorizing Resources 'https://dummyjson.com/docs#intro-auth'). 
    Example: 'https://dummyjson.com/auth/posts'


## 🥇 Hard Level

### Tasks
- [ ] Implement axios interceptor to pass auth token with requests.
- [ ] Handle API errors in axios interceptor response.
- [ ] Create ThemeToggle button that changes the theme of your application from dark/light to light/dark using Context API
- [ ] Implement ADD, UPDATE, DELETE post features


Happy coding! 🎉