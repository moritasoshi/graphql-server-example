## GraphQL Server with Apollo

```sh
# Run graphql server
$ npm start

# and call apis with cURL
$ curl --request POST \
          --header 'content-type: application/json' \
          --url http://localhost:4000/ \
          --data '{"query":"query{books{title author}}"}'

{"data":{"books":[{"title":"The Awakening","author":"Kate Chopin"},{"title":"City of Glass","author":"Paul Auster"}]}}
```
