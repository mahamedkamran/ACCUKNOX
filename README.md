# STEPS

## 1. Create the Dockerfile as below:
![wisecow](https://github.com/mahamedkamran/ACCUKNOX/blob/main/images/Dockerfile.png)

## 2. Deployment.yaml file:
![](https://github.com/mahamedkamran/ACCUKNOX/blob/main/images/Deployment_file.png)


## 2. Service.yaml file:
![](https://github.com/mahamedkamran/ACCUKNOX/blob/main/images/service_yaml.png)
## Requirement
1. Create Dockerfile for the image and corresponding k8s manifest to deploy in k8s env. The wisecow service should be exposed as k8s service.
2. Github action for creating new image when changes are made to this repo
3. [Challenge goal]: Enable secure TLS communication for the wisecow app.

## Expected Artifacts
1. Github repo containing the app with corresponding dockerfile, k8s manifest, any other artifacts needed.
2. Github repo with corresponding github action.
3. Github repo should be kept private and the access should be enabled for following github IDs: nyrahul, SujithKasireddy
