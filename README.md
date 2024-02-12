# cloud_assignment

Please update below variables in input.tfvars before you deploying the components in AWS

1. aws_account_num
2. aws_region: I am using "us-east-1", you can provide your region
3. ecr_repo_name: I am using ecr repo name as "dxc_assignment" with latest tag 
4. container_port, I am using default port "80", you can use on the basis of your image exposed port.
5. cpu & memory: I using mimimum as cpu=256 mb & memory=512
6. desired task count as 2.
7. alb_target_value_for_scaling: For auto scaling I am using alb target scalling count as 10 for scale
8. autoscaling_max_task as "4"



