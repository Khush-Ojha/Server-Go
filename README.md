# Go HTTP Server

A simple HTTP server built in Go that demonstrates:

- Serving static files
- Handling GET requests
- Handling POST requests using FormValue
- Basic routing with http.HandleFunc
- Running a local server on port 8080

This project is ideal for beginners learning Go backend development.

---

## Project Structure

├── main.go
├── go.mod
├── static/
│ ├── index.html
│ └── form.html

---

## Features

### Serve Static Files

The root route `/` serves HTML files from the static folder.

### GET Route

`/hello` responds with a simple text message.

### POST Route

`/form` handles form submissions and prints:

- name
- address

---

## Running the Server

### Start the server:

### Open in browser:

- Home:  
  http://localhost:8080/

- Form page:  
  http://localhost:8080/form

- Hello endpoint:  
  http://localhost:8080/hello

---

## Example cURL Test

Test a POST request:
