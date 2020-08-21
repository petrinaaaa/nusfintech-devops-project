# Currency Exchange API – NodeJS

Node.js CI workflow: test node.js
- This workflow tests the node.js code using the JEST framework whenever a push is made
- On telegram, add DevOps_bot and click /start
- When the workflow is completed, a telegram notification will be sent to DevOps_bot

Docker image CI workflow: build and push Docker images
- This workflow builds and push a Docker image whenever a push is made
- You can change the Docker repository that the image is being pushed into by changing the secret key {{DOCKER_USERNAME}} and {{DOCKER_PASSWORD}}

