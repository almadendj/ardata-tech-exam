# ARData Exam Project Monorepo

This repository contains the source code for the ARData Exam project, which is split into three main components:

- **Frontend**: A web interface for user interaction.
- **Backend**: The server-side logic written in Rust.
- **Smart Contract**: Blockchain smart contracts (not detailed in the Docker setup).

## Directory Structure

- `/ardata-exam-frontend` - Contains the frontend code.
- `/ardata-exam-backend` - Contains the backend code.
- `/ardata-exam-smart-contract` - Contains smart contracts for blockchain interaction.

## Prerequisites

Before you begin, ensure you have Docker and Docker Compose installed on your machine. Visit [Docker's official website](https://docs.docker.com/get-docker/) for installation instructions.

## Configuration

### Backend Environment

The backend service requires an environment file `.env` located in the `/ardata-exam-backend` directory. This file should contain all the necessary environment variables needed for the backend service.

Example of `.env` file content:
```plaintext
API_KEY=<API_KEY>
API_URL=https://eth-mainnet.g.alchemy.com/v2/
```

## Running the Services

To start all services, navigate to the root of the monorepo and run the following command:
```bash
docker compose up -d

```
