{
  "name": "Windows 11 Cloud PC",
  "dockerComposeFile": "../docker-compose.yml",
  "service": "windows",
  "workspaceFolder": "/storage",
  "features": {
    "ghcr.io/devcontainers/features/docker-in-docker:2": {}
  },
  "customizations": {
    "vscode": {
      "settings": {}
    }
  },
  "forwardPorts": [8006, 3389]
}


