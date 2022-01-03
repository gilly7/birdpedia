# birdpedia
A web application in Go (golang) to display the different entries submitted by the community, with the name and details of the bird they found. and allow anyone to post a new entry about a bird that they saw.

To run the server on your system:

1. Run `go build` to create the binary (`birdpedia`)
1. Run the binary : `./birdpedia`

To run tests, run `go test ./...`


# This website :

- Displays the different entries submitted by the community, with the name and details of the bird they found.
- Allows anyone to post a new entry about a bird that they saw.

# This application require three components :

- The web server
- The front-end (client side) app
- The database 
-
![Image summary](https://www.sohamkamani.com/static/a3973f373cbc863a85be21d1ec92a551/d00b9/blog-golang-web-app-arch.webp)

# Steps/commits I took for this repo
- Creating the project directory
- Starting an HTTP server
- Making routes
- Installing external libraries
- Testing. Testing is an essential part of making any application “production quality”. It ensures that our application works the way that we expect it to.
- Making our routing testable. Ensure that each handler is mapped to the correct HTTP route.
-  Serving static files.
“Static files” are the HTML, CSS, JavaScript, images, and the other static asset files that are needed to form a website.


# There are 3 steps to take in order to make our server serve these static assets.

1. Create static assets
2. Modify our router to serve static assets
3. Add tests to verify that our new server can serve static files


- Making a simple browser app.
- Adding the bird REST API handlers.

- Last step: Adding a database


