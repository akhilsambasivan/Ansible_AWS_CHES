IaC with Ansible for setting up CHES in AWS:
------------------------------------------
- VPC service (Create VPC service / Subnet / IGW / Route / Security Group for CHES)
- EC2_instance (Create EC2 instaces for CHES)
- S3_service (Create and manage S3 buckets for CHES)
- CloudFront_service (Create and manage CloudFront service for CHES)
- Lamda_service (Create and manage Lamda service for CHES )
- SNS_service (Create and manage SNS service for CHES)
- SQS_service (Create and manage SQS service for CHES)

Variables for each role is defined in group_vars as global variables.
