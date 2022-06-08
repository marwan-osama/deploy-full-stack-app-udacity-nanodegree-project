## Infrastructure description

### Application Api: 
the application API is built based on node, express and deployed on AWS Elasticbeanstalk service to deal with the database and handle frontend application requests

available at: http://udagram-env-1.eba-9v3qie3v.us-east-1.elasticbeanstalk.com/.


- **Application frontend**: 
the application front is built based on angular framework and deployed on AWS S3 service to make requests to the API application based on the client actions.

available at: http://udagram-123.s3-website-us-east-1.amazonaws.com.

### capplication database: 
application database in based on postgres database and hosted on AWS relational database service (RDS) to serve/store data for the API application.