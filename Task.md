- Use different Node.js base images and understand their differences:
  1. node:18
  2. node:18-slim
  3. node:18-alpine
- Write Dockerfiles from scratch and experiment with using .dockerfile instead of the default Dockerfile.
- Create a common Docker network to allow all containers in your application to communicate:
- Use docker network create and --network flag when running containers.
- Use environment variables in different ways:
  - Define them in a .env file.
  - Pass them directly in the terminal using -e KEY=value.
  - Set them inside the Dockerfile using ENV KEY=value.
  - Use --env-file .env while running containers to securely inject variables.
- Write your own docker-compose.yml file to manage multi-container applications with ease.
