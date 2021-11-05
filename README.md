# Terraform Group Exercise - Deploy Web App

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/SERC-Terraform-Labs/group-exercise---deploy-web-app-kca)

(You might need to wait a minute and refresh the page before the Gitpod link works.)

Group exercise to use a pipeline to provision a VM and deploy a web app to it.

## Exercise

In your group, create a deployment pipeline that will create or update a VM and deploy a web app to it. Infrastucture code and pipeline configuration should be stored in this repo. New changes to this repo should trigger a re-deployment.

The web app is in the `src/` directory.

### Hints

- State will need to be stored somewhere to allow for updating infrastructure.
- The public IP address of the VM should be output by the pipeline so that the web app can be visited.
- Bonus points if the pipeline includes tests.
