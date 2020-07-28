Before starting the app, you should do the following:
- Create folder and in this directory in terminal write 'npm init -y'
- Install express (npm install express)
- Install express-graphql (npm install express-graphql)
- Install graphql (npm install graphql)

Start app.js in your terminal uisng node app.js, then go to the http://localhost:3000/graphql and try the folowing  query 

{
  post(id: 1) {
    title
    description
    author {
      name
      age
    }
  },
  posts {
    title
    description
    author {
      name
      age
    }
  }
}