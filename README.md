**MintHCM Docker Deployment Repository**

This repository provides a comprehensive Docker Compose setup for deploying MintHCM, a robust CRM application, in a containerized environment. MintHCM is ready to go with this easy-to-use Docker configuration.

**Features:**

- **Containerized Deployment:** Deploy MintHCM effortlessly using Docker Compose.

- **Configuration Options:** Customize your MintHCM installation by adjusting variables in the `.env` file. Modify parameters such as the web port, database details, and MintHCM admin credentials.

**Instructions:**

1. Clone this repository to your local machine:
```
git clone https://github.com/bascheffler/minthcm-docker-compose.git
cd minthcm-docker-compose
```

2. Customize Settings:
- Edit the `.env` file to tailor parameters.

3. Launch MintHCM:
```
docker compose up -d
```
4. Monitor Progress:
```
docker logs --follow <name_of_minthcm-web_container>
```
5. Access MintHCM:
- Open your web browser and access MintHCM at `http://localhost` or the configured IP and port.

6. Configuration Changes:
- If you wish to make changes to the `.env` file, create a fresh environment to ensure MintHCM is installed with the new parameters.

7. Enjoy MintHCM:
- Log in to MintHCM using the admin credentials specified in the `.env` file and start managing your CRM operations.

⚠️ **Important:** This Docker Compose setup is intended for demonstration and testing purposes only. We do not recommend using this configuration in a production environment.

**Note:**
- Docker and Docker Compose must be installed on your system.

Docker Hub: https://hub.docker.com/repository/docker/minthcm/minthcm/general
