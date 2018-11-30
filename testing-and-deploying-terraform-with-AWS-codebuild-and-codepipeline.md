## Testing and deploying Terraform with AWS CodeBuild and CodePipeline

At dxw we are building a system to deploy apps to AWS ECS for clients in a secure and scalable way, using a mixture of Terraform and Ruby.

We use CodePipeline to deploy our Terraform continuously, and to make sure we don't break the running applications we test the Terraform with CodeBuild.

Find out how and why we use CodeBuild and CodePipeline, as well as the issues we found along the way and what we plan for the future.
