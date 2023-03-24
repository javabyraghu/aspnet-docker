# aspnet-docker
Simple demo of ASP.NET Core and Docker using .NET Core 3.1 LTS.

## Requirements
In order to run this example, you'll need to have installed on your machine (Windows, Mac, Linux):
* Docker Desktop (or Docker on Linux)
* .NET Core SDK 3.1

## Running
The steps to run are:
1. clone this tool: `git clone https://github.com/hd9/aspnet-docker` 
2. cd into the folder: `cd aspnet-docker`
3. Build a docker image: `docker build . -t webapp`
4. Run a container with: `docker run --rm -it -p 8080:80 webapp`
5. Open your browser and navigate to: `localhost:8080`

