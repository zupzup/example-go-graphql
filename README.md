# example-go-graphql

Example of using Go to create a graphql API

Start with `go run main.go`

Go to `http://localhost:3000/graphql` using [GraphiQL](https://github.com/graphql/graphiql)

Set off queries such as:

```
query {
  post(id: 5) {
    userId
    id
    body
    title
    comments {
      id
      email
      name
    }
  }
}
```
