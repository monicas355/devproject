# Sample Dockerized Node.js Project

This repository contains a simple Node.js application that can be built and run using Docker.

## Project Structure

- **src/**: Contains the source code.
- **tests/**: Contains test files.
- **Dockerfile**: Defines how to build the Docker image.
- **.github/workflows/**: Contains GitHub Actions CI/CD workflows.
- **package.json**: Lists dependencies and scripts.

## How to Run

### Run Locally

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the app:
   ```bash
   npm start
   ```

3. Open [http://localhost:3000](http://localhost:3000).

### Run with Docker

1. Build the Docker image:
   ```bash
   docker build -t username/project .
   ```

2. Run the Docker container:
   ```bash
   docker run -p 3000:3000 username/project
   ```

3. Open [http://localhost:3000](http://localhost:3000).

### Tests

Run tests with:
```bash
npm test
```
