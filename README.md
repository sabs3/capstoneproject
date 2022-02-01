[![CircleCI](https://circleci.com/gh/sabs3/capstoneproject/tree/main.svg?style=svg)](https://circleci.com/gh/sabs3/capstoneproject/tree/main)

Capstone Project - This project recycles Sklearn mlmodel prediction code with added below functionality:

1) Lints over Dockerfile prior to Image build
2) On successful lint, uploads latest image to docker hub with the CircleCI job ID tag
3) Deploys a EKS cluster within AWS eu-west-2 and deploys newly built image into kubernetes cluster
4) Smoke tests to confirm application is available via loadbalancer service
5) Deletes previous kubernetes deployment and cluster