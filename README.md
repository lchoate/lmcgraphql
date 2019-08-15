# Node Based GraphQL Server
Contains a basic dataset of books and authors

## Project setup
Ensure you have node.
```
git clone <path to repo>
```
### Install packages
````
yarn install
````

### Run the dev server
```
nodemon server.js
```
### Use the Client
http://localhost:5000/graphql

### Or just use postman

````
{
  author(id:1) {
    name
    books {
      name
    }
  }
}
 ````