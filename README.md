
# Git Hub Finder 
 It is an application for finding a Git Hub User by its name or username.




## Installation

Install this Project with npm

```bash
  npm install
  
```


## API Reference

#### Get users by Name or Username:

```http
https://api.github.com/search/users?q=${text}&client_id=${<YOUR GITHUB CLIENT_ID>}&client_secret={<YOUR GITHUB CLIENT_SECRET>}

```


#### Get user Repositories :


```http
https://api.github.com/users/${username}/repos?per_page=5&sort=created:asc&client_id=${<YOUR GITHUB CLIENT_ID>}&client_secret={<YOUR GITHUB CLIENT_SECRET>}

```

##  Tech Stacks

### React Js

    React helps you create your web applications in a more maintainable way.
    React enables developer to reuse components.  

### Axios

    Axios is a library used in this project to make request to API ,return data form API , then do the things from that data.
    It has good defaults to work with JSON data. Unlike alternatives such as the Fetch API, you often don't need to set your headers. Or perform tedious tasks like converting your request body to a JSON string.
    Axios has function names that match any HTTP methods. To perform a GET request, you use the .get() method.

### React-Router
    I have used React-Router for Routing in this web application which  enables the navigation among views of various components in a React Application, allows changing the browser URL, and keeps the UI in sync with the URL.
#### Components used from react-router-dom
    1. BrowserRouter :- BrowserRouter is a router implementation that uses the HTML5 history API to keep your UI in sync with the URL. 
                        It is the parent component that is used to store all of the other components.

    2. Route :-         Route is the conditionally shown component that renders some UI when its path matches the current URL.  

    3. Switch :-         Switch component is used to render only the first route that matches the location rather than rendering all matching routes.

    4. Link :-           Link component is used to create links to different routes and implement navigation around the application. It works like HTML anchor tag.

   
##  Sample Screenshots

![image](https://user-images.githubusercontent.com/91049345/140654863-49b2b9fd-9871-4e33-b90e-4995defaced1.png)

### User List : 

![image](https://user-images.githubusercontent.com/91049345/140654920-3153ad9d-f6a1-4575-b039-366823e04ad9.png)

### User Details : 
![image](https://user-images.githubusercontent.com/91049345/140654956-f366bf2b-149b-416d-a68e-fae7453f560f.png)
## Author

- [@rushikesh-mahamuni](https://github.com/rushikesh-mahamuni)

