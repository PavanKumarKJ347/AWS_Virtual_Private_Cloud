
# End to End CICD Pipeline Project

## This Project can be used to Build an End to End CICD Pipeline.

## CICD Pipeline Stages

- Checkout Code from GitHub.
- Build Project.
- Execute SonarQube Test.
- Upload Build Artifact to Sonatype Nexus.
- Build Docker Image.
- Push Docker Image to Docker Hub Registry.
- Remove Docker Image Locally in Jenkins.
- Update Docker Image Tag in Kubernetes Manifest.
- Deploy Application into Kubernetes Cluster.
- Send CICD Pipeline Execution Status to Slack.


![CICD](https://github.com/PavanKumarKJ347/AWS_Virtual_Private_Cloud/blob/main/AWS_Virtual_Private_Cloud.jpeg?raw=true)
  

Note:
Application can be deployed to Kubernetes Cluster using Kubernetes Manifest Files as well as Helm Chart.
