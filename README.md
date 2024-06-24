How to start working with the template

After downloading and unziping the folder:
    - Open package.json and change some settings if wanted

When wanting to start working on the new project:
    - In the console, run the command: docker-compose -f docker-compose-dev.yml up --build (Later, you don't need the flag --build because it initialises a new image)
    - Go on the port 3000, the changes in /src are in sync with the docker container so the changes will be reflected instantly.

When project is ready for production:
    - In the console, run the command: docker-compose -f docker-compose-prod.yml up --build
    - Go on the port 8080.
