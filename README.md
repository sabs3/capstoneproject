[![CircleCI](https://circleci.com/gh/sabs3/capstoneproject/tree/main.svg?style=svg)](https://circleci.com/gh/sabs3/capstoneproject/tree/main)

Capstone Project - This project recycles Sklearn mlmodel prediction code with added below functionality:

1) Github repository created with project code: https://github.com/sabs3/capstoneproject
2) Executes liniting step in code pipeline
2) On successful lint, docker images is build using Dockerfile and pushed to the docker centre repository.
3) Deploys a EKS cluster and deploys latest built  to a kubernetes cluster.
4) Smoke tests is run to confirm application is available via loadbalancer service
5) Deletes previous kubernetes deployment and cluster

\includegraphics[]{screenshots/lint_failing.png}
\includegraphics[]{screenshots/lint_sucess.png}
\includegraphics[]{screenshots/pipeline.png}
\includegraphics[]{screenshots/successful_deployment.png}
