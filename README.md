# Reusable-workflow

## About
The reusable-workflow to avoid duplication when creating a workflow by reusing existing workflows
## Step
- checkout code
- Configure AWS Credentials with the role to assume, this role is used for pushing docker image to aws ecr ( no need to use aws keys)
- Tag docker image based on event tag
- Login to Amazon ECR
- Build and push Docker image
- Prepare values for dispatch
- Deploy dispatch
