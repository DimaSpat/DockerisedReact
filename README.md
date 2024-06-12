How to start working with the template

After downloading and unziping the folder:
    - Open package.json and change some settings if wanted

When wanting to start working on the new project:
    - In the console, run the command: docker-compose up
    - After everything initialised and you see the local port, split the terminal
    - Then in the new terminal run the command: docker-compose watch
    it gives the ability to see the changes from the code live.

Also if not working, you can start this way:
    - docker build -t client:latest .
    - docker run -p 3000:3000 -it client:latest
