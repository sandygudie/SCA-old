# SCA-Cloud-School-Application
Creating a dockerfile with Node js

### Running the project locally
- Fork this repository
- Clone to your local machine
- checkout to the branch stable
- `cd` into the repository and run `npm install && npm start`
- Go to http://localhost:8080
A welcome message "Welcome to SCA Cloud School Application" will show on the browser

###To deploy to Docker
-Open An account with Docker docker.com and download the docker hub
-To build Docker image - Type  `docker build -t dockerdemo` 
-To run the Docker image - `docker run -p 49160:8080 -d dockerdemo`
