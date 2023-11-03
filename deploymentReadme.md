# Purpose
In the prior deployment, the application was distributed across multiple regions using Terraform as the infrastructure-as-code tool, in conjunction with a Jenkins server-agent architecture. To optimize cost-effectiveness, resource utilization, and deployment efficiency, the application will be deployed using Amazon Elastic Container Service (ECS) in conjunction with the Docker engine. Containerization of the application offers the company the flexibility to automatically scale multiple containers on a single virtual machine as required, ensuring rapid responsiveness to changing workload demands. These containers will be efficiently managed through the ECS service.

# Issues
# Steps
### Step 1
Create a docker file with the necessary configurations and instrcutions. Be sure to use the following for this application:
  - Python:3.7
  - Code Repository: https://github.com/DarrielleEvans/deployment6.git
  - Dependencies: pip install -r requirements.txt, pip install gunicorn

### Step 2


# System Diagram (Your diagram must include the default VPC and ECS VPC)
# Optimization (How would make this deployment more efficient, if you utilize ChatGPT make sure to explain what your prompt was.)
