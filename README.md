# harness-custom-delegate
Pipeline and Dockerfile for creating a Harness Delegate with custom tools pre-installed

### Example Build Command:

```
docker build -f Dockerfile-terraform --build-arg BASE_IMAGE_TAG=23.02.78904 --build-arg TERRAFORM_VERSION=1.4.4 -t konrness/harness-delegate-terraform:23.02.78904 .
```