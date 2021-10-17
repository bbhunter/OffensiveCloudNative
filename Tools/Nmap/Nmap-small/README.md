# Docker - Nmap (Alpine)

A Dockerized version of the tool Nmap that is small and works on Raspberry pi

Recommended: Local build is recommended for Raspberry pi because the Docker daemon will automatically pull down the alpine image that matches the host architecture

## Running with Docker (Local build)

```docker build -t nmap-small .```

Build the container (locally)

```docker run -it nmap-small <arguments> <target>```

Run nmap with arguments

## Running with Docker (Docker Hub)

```docker run -it sneakerhax\nmap-small <arguments> <targets>```

Start image pulled from Docker Hub and run Nmap with target