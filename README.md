# harness-custom-delegate
Pipeline and Dockerfile for creating a Harness Delegate with custom tools pre-installed

### Example Build Command:

```
docker build -f Dockerfile-terraform --build-arg BASE_IMAGE_TAG=23.02.78306 --build-arg TERRAFORM_VERSION=1.3.5 -t konrness/harness-delegate-terraform:23.02.78306 .
```