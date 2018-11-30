## Testing and deploying Terraform with AWS CodeBuild and CodePipeline

At dxw we are building a system to deploy apps to AWS ECS for clients in a
secure and scalable way. We are doing this with a mixture of Terraform and Ruby.

To make sure we don't break the running applications when we deploy our Terrform
continuously with CodePipeline we test our Terraform with CodeBuild using a
variety of tools

Find out why and how we use CodeBuild and CodePipeline to achieve
this. The issues we found along the way and the what we plan for the future.

