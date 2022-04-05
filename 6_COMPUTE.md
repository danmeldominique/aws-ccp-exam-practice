# Overview

Other compute services: ECS, Lambda, Batch, Lightsail

- **Docker:** Container technology that runs applications
- **ECS:** Runs docker containers on EC2 instances
- **Fargate:** Run docker images without provisioning infrastructure. Serverless.
- **ECR:** DOcker repository. Similar to Docker Hub.
- **Batch:** Run batch jobs across managed EC2 instances.
- **Lightsail:** Predictable, low pricing for simple app and DB stack.
- **Lambda:**
  - Serverless, Function as a Service (FaaS). Seamless, Scalable
  - Pay per invocation and (time run x ram provisioned)
  - Language support: Many supported, except Docker
  - Run time: Up to 15 minutes
  - Use Case -> Serverless cron job, create thumbnails
- **API Gateway:** Expose Lambda functions as HTTP API