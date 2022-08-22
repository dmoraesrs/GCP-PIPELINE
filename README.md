## This project introduces git actions integration with GCP:
Stages Project:

1. Build em Push Docker Image
2. Deploys Applications in Kubernetes(GKE)


## 1. Build em Push Docker Image
For this study, github actions with CI\CD mat was used.
The environment was divided into Production and Development, for that the resource of environments so git actions was used.

![environments:](https://github.com/dmoraesrs/images/blob/master/actions2.png)


In this resource, the secrets with the information to be used in the deploy were registered.

![Secrets:](https://github.com/dmoraesrs/images/blob/master/actions1.png)


Pipeline Execution Result

![Pipeline:](https://github.com/dmoraesrs/images/blob/master/actions3.png)


In the docker-publish.yml file we have described the docker image generation and publishing pipelines in the GCP registry
