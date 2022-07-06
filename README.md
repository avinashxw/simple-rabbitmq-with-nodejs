# simple-rabbitmq-with-nodejs
Here publisher sends a job to be executed and consumer consumes it


Run below commands:

# this runs and check whether docer exists or not, if not please download and install docker in your local system
docker

# this runs and responds with message "Hello from Docker!" 
docker run hello-world

# this will cretae rabbitmq image locally and let this be running in one of your terminal
docker run --name rabbitmq -p 5672:5672 rabbitmq

# after taking the clone of this repo, run following commands
npm install

# open below commands in  two different terminals to analyse the result 
npm run publish

npm run consume