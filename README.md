# GP-1 Go Web Server

A simple Golang web server that serves three routes:

- `/`
- `/hello`
- `/form`

To access the form, navigate to:  
`http://localhost:8080/form.html`

---

## Features

- **Root Route (`/`)**: A basic homepage.
- **Hello Route (`/hello`)**: Greets the user.
- **Form Route (`/form`)**: Serves a form where users can input data.

---

## Getting Started

Follow these steps to clone, build, and run the server locally.

### Prerequisites

- [Go (Golang)](https://golang.org/doc/install) installed on your machine.

---

### Steps to Run Locally

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd gp-1-go-web-server
   ```
2. **Build the Application**
   ```bash
   go build
   ```
3. **Run The Executable**
   ```bash
   ./gp-1-go-web-server
   ```
4. **Access the server**

   Open your browser and navigate to:

   - http://localhost:8080/
   - http://localhost:8080/hello
   - http://localhost:8080/form.html
