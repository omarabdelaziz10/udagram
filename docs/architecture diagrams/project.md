## Udagram Infrastructure

![Architecture flow](architectureDiagram.png)

# AWS
#### RDS database
Database endpoint: `postgres.cybxu07myc9a.us-east-1.rds.amazonaws.com`

#### Elastic Beanstalk
server is running on EBS depending on the database

server url : `http://udagram-api-dev.eba-922mbvda.us-east-1.elasticbeanstalk.com`

#### S3
front end is uploaded on S3 for static web hosting,
app url : `http://udagram-omar1020.s3-website-us-east-1.amazonaws.com`