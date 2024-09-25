# Sample MERN with Microservices

## Objective
1. Write docker file and docker-compose file.
2. Push images to ECR.
3. Create a Kubernetes cluster and deploy the application using minikube on localhost.
4. Create a Kubernetes cluster and deploy the application using EKS

## Concepts/Technology/Tool Covered
1. Kubenetes
2. AWS EKS
3. Docker
4. Git & Github
5. AWS ECR

## Steps
* For `helloService`, create `.env` file with the content:
```bash
PORT=3001
```
* For `profileService`, create `.env` file with the content:
```bash
PORT=3002
MONGO_URL="specifyYourMongoURLHereWithDatabaseNameInTheEnd"
```
> For both frontend & backend install packages in all the 3 services by running the command `npm install` from their root directory.
* Run the backend(helloService & profileService) with `node index.js`.
* Run the frontend with `npm start `. 
* For IAC follow this [IAC for MERN microservice](https://github.com/yashbhatt1304/iac-for-mern-microservice.git)

## References & Links

## Happy Coding
Thanks for continuing till the End. :)

