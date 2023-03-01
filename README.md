
## 🛠 Skills
Node.js, HTML, CSS,Rest API,Express.js....


# Newsletter-Signup

The code starts by requiring the express module. It then creates an app object and assigns it to the variable "app". The code then uses request to make a GET request for "/" with no parameters. This will send back the file public/signup.html, which is where users sign up for their account on our site. The next line of code makes a POST request to / with two parameters: firstName and lastName, which are variables that represent user input from the form in signup.html. The email parameter is also included as part of this POST request because we need it in order to create an account on our site using Express's body-parser middleware package (which we require at the top). We use JSON stringify() function here so that data can be sent back as JSON instead of just plain text when posting data through Express's response object (which we require at the bottom).
The code is a snippet of code that will be used to create an Express application. The first line in the snippet above is a call to require("express"). This is followed by a call to app.use(bodyParser.urlencoded({ extended: true })); This means that body-parser will be used for all requests made on this server, and it will also use url encoding for any request bodies that are sent with these requests. Next, we see the call to app.get("/", (req, res) => { res.sendFile(__dirname + "/signup.html"); }); This means that when someone goes to http://localhost:3000/, they'll see the file "signup


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Documentation

[Documentation](https://linktodocumentation)


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## Running Tests

To run tests, run the following command

```bash
  npm run test
```


# Hi, I'm Vishal! 👋


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishal-ramteke95/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)

