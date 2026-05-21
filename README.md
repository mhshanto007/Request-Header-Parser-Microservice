# Request Header Parser Microservice

A simple Request Header Parser Microservice built with Node.js and Express.

## Features

- Get client IP address
- Get preferred language
- Get browser and operating system information
- Simple REST API endpoint

---

## Technologies Used

- Node.js
- Express.js

---

## API Endpoint

### Get Request Header Information

```bash
/api/whoami
```

Example Response:

```json
{
  "ipaddress": "103.xxx.xxx.xxx",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/148.0.0.0 Safari/537.36"
}
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/mhshanto007/request-header-parser-microservice.git
```

Go to the project folder:

```bash
cd request-header-parser-microservice
```

Install dependencies:

```bash
npm install
```

Start the server:

```bash
node server.js
```

---

## Live Demo

https://request-header-parser-microservice-5c0j.onrender.com/api/whoami

---

## Author

GitHub: https://github.com/mhshanto007