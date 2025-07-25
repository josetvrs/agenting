# N8N w/OLLAMA

### This project includes a docker compose file to run n8n with ollama locally in your machine using docker.

## STEPS
1. Install Docker and Docker Compose in your machine
2. Pull ollama/ollama docker image (to run and manage AI models)
3. Pull n8nio/n8n docker image (to create AI agent worflows)
4. Run docker-compose up

## ABOUT
Uses docker compose to simply run both ollama and n8n docker containers and allow them to interact with each other.
It could be needed for you to create en .env file with the following values if you want to use n8n authentication

N8N_USER="your_n8n_username_or_email"
N8N_PSSWD="your_n8n_password"

