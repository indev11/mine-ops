🚀 What It Does
This Ansible playbook sets up a fully functional Minecraft server on a Linux system with just one command. Here’s the magic it performs:

Installs Dependencies: Sets up Java (openjdk-17-jdk) and jq for JSON parsing.
User & Permissions: Creates a minecraft user and group, plus a dedicated directory (/opt/minecraft).
Downloads the Server: Fetches the latest or a specific version of the Minecraft server JAR from Mojang’s official source.
Configures the Environment: Copies the EULA, sets up a systemd service, and opens firewall ports (25565 TCP/UDP).
Launches the Server: Starts the server, disables online mode, and verifies it’s running by checking logs.
