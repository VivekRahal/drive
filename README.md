# Drive — Cloud Computing Web App

A simple Express.js web application built as part of the **IACSD CDAC Training Centre** coursework, containerized with Docker for cloud deployment.

## About

This is a basic Node.js web server demonstrating:
- Setting up an Express.js application
- Defining route handlers for different endpoints
- Containerizing a Node.js app with Docker

## Courses at IACSD CDAC

1. **DAC** — Diploma in Advanced Computing
2. **DBDA** — Diploma in Big Data Analytics
3. **DITISS** — Diploma in IT Infrastructure, Systems and Security

## Endpoints

| Route | Description |
|-------|-------------|
| `GET /` | Homepage — displays company info and service offerings (products, cloud solutions, careers, corporate training) |
| `GET /aboutus` | About Us page — displays CEO information |

## Tech Stack

- **Runtime:** Node.js 7
- **Framework:** Express.js 4.x
- **Containerization:** Docker

## Getting Started

### Local Development

```bash
# Install dependencies
npm install

# Start the server
npm start

# Visit http://localhost:8081
```

### Docker

```bash
# Build the image
docker build -t drive-app .

# Run the container
docker run -p 8081:8081 drive-app

# Visit http://localhost:8081
```

## Project Structure

```
drive/
├── server.js        # Express app with route handlers
├── package.json     # Node.js dependencies and scripts
├── Dockerfile       # Container configuration
└── README.md
```

## License

Open-sourced for educational purposes.
