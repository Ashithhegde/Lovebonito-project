Step 1 : Run the terraform gilab-ci to deploy the Kubernetes cluster on to AWS Cloud

Step 2: Build the new docker image using Dockerfile from " love-bonito/password-manager" and save as "myapp" and new gitlab-ci and push image to repo

docker build -t myapp

docker run -p 8080:8080 myapp

Step 3: Create the Deployment config file "deployment.yaml" 

Step 4: Run kubectl apply -f deployment.yaml

Step 5: docker run -p 8080:8080 