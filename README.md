# 🐳 Portainer Docker Compose

This repository provides a Docker Compose configuration to quickly set up Portainer, an open-source container management tool. Portainer allows you to manage your Docker environment through a user-friendly web interface.

## 🛠️ Prerequisites

Before getting started, make sure you have the following installed:

- Docker Engine
- Docker Compose

## 📚 Usage

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. ⚙️ Customize the sample service configuration:

- Copy the sample `docker-compose.yml.example` file:
  
  ```bash
  cp docker-compose.yml.example docker-compose.yml
  ```

3. Navigate to the cloned repository:

    ```bash
    cd portainer-docker-compose
    ```

4. Customize the Docker Compose file (docker-compose.yml) if needed. You can modify the Portainer version, ports, volume names, etc., according to your requirements.

5. Start Portainer using Docker Compose:

    ```bash
    docker-compose up -d
    ```

6. Access Portainer's web interface:

    Open your preferred web browser and go to https://localhost:9443.

    Note: If you're running Docker on a remote machine or a different port, replace localhost with the appropriate hostname or IP address, and update the port number accordingly.

7. Follow the on-screen instructions to complete the initial setup of Portainer. You will be prompted to create an admin user and set a password.

8. Once the setup is complete, you can start managing your Docker environment using Portainer's intuitive web interface.

## 📄 License

MIT / BSD

## 🇬🇧🇭🇰 Author Information

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Website: https://www.jodywan.com