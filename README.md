# Belajar GraphQL
Belajar graphQL server menggunakan biolerplate dari apollo-starter-kit.

# Dependencies
# use
* npm install
* npm start 
* open localhost:8080/graphql

ambil salah satu fake username di console.log terminal, contoh saya mengambil nama "Edmond"

{
  author(firstName: "Edmond") {
    firstName
    lastName
    posts{
      title
      text
      views
      author{
        firstName
        lastName
      }
    }
  }
  getFortuneCookie
}

copypaste query diatas di graphiql 