# THREE TIER INFRASTRUCTURE EXPERIENCE:

![Gravity_Infra_New](https://user-images.githubusercontent.com/76897910/187633319-63ad108a-61f5-4ebc-a19f-824da3b745c5.jpg)

# AWS SERVICES USED:
# # Front-end

   - Cloudfront
   - S3-static webhosting
   - DNS - ROUTE 53 / Go-Daddy

# # API-BACKEND:
   
   - Elastic beanstalk multiple envirorments - cross api
   - RDS - Postgres sql
   - Private-api s3 buckets
   - EC2-instance for deployment , migration on elasticbeanstalk / RDS through cli

# # PUSH NOTIFICATION SERVICES:
   
   - FIREBASE / IOS integration using SNS
   - Amazon Simple Email Service
   
# # VPC:

   - IGW > Routable > SUBNETS
        - PUBLIC SUBNETS >REGION A,B,C > Elastic beanstalk instances , loadbalancer , NAT GATEWAY , Cron-Queue server
        - PRIVATE SUBNETS > REGION A,B,C > MULTI-AZ RDS
        
  
   
