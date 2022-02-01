[![CircleCI](https://circleci.com/gh/sabs3/capstoneproject/tree/main.svg?style=svg)](https://circleci.com/gh/sabs3/capstoneproject/tree/main)

Capstone Project - SkLearn Application Deployment pipeline

This project has bellow functionality:

1) Lints over docker files prior to Image build
2) Uploads Image to docker hub with the CircleCI job ID tag
3) Deploys a EKS cluster within AWS and deploys newly built container image into kubernetes
4) Smoke test to confirm application is available
5)Deletes previous infrastructure deployment