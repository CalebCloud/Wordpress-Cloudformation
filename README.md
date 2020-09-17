# Wordpress-Cloudformation
Cloudformation template to create Wordpress website on an EC2 instance using an RDS mysql database, all in a newly created VPC with a new route53 record to host the website in a subdomain on an existing hosted zone.



Requirements: 
- Route 53 Hosted Zone

Changes to make: 
- Change initialDomain on Route53.yaml to your Route53 domain
- Upload RDS/VPC/EC2/Route53 files to S3
- Change master TemplateURL under each stack to reflect the new S3 URL's
