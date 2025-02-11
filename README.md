# Mbuso The Chatbot

A personalized AI chatbot built with Go that simulates conversations with a digital version of Mbuso Mgobhozi. The chatbot maintains context and personality through Redis-based session management.

## Features

- Personalized AI responses based on a detailed personality prompt
- Session management using Redis
- Docker containerization for easy deployment
- Web-based chat interface
- OpenAI integration for natural language processing

## Prerequisites

- Docker and Docker Compose
- Go 1.x
- OpenAI API key

## Tech Stack

- **Backend**: Go
- **Memory Store**: Redis
- **AI Model**: OpenAI
- **Containerization**: Docker

## Getting Started

1. Clone the repository
2. Set up your OpenAI API key as an environment variable
3. Run the application using Docker Compose:

```bash
docker-compose up --build
```

The application will be available at `http://localhost:8080`

## Project Structure

```
├── main.go           # Main application code
├── Dockerfile        # Docker configuration
├── docker-compose.yaml # Docker Compose configuration
├── static/           # Static files directory
└── README.md         # Project documentation
```

## Environment Variables

- `REDIS_ADDR`: Redis server address (default: redis:6379)
- `OPENAI_API_KEY`: Your OpenAI API key

## License

This project is licensed under the terms of the license included in the repository.