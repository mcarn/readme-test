# GraphQL Example Project


### What is this repository for?

* Serves as introduction to GraphQL

## Getting Started

* Run the project using your IDE
  * You could install GraphQL playground to get a GUI to test the application
  * Alternatively you could enter [http://loclhost:8080/graphiql]() in your browser and a GUI will be provided for you
* Query structure:
  ```graphql
  query{
    shows{
    releaseYear
    title
    }
    }
  ```
  * Mutation structure:

```graphql
    mutation {
      addShow(show:{title: "HIMYM", releaseYear:2010}) {
      releaseYear
      title
      }
      }
```
