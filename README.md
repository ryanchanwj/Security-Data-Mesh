# AWS Security Data Mesh 


<br/>
This guide runs through how a data mesh architecture can be deployed on AWS using AWS Lake Formation and AWS Glue services to minimise blast radius and federate data governance in a scalable manner. 

5 AWS CloudFormation templates are provided for the data mesh architecture setup - the central governance, producer1, producer2, consumer1 and consumer2 accounts. Take note of the AWS account IDs for the 5 accounts and deploy the CloudFormation templates in the order of central governance account, producer accounts and consumer accounts due to their dependencies. A detailed walkthrough of the deployment steps can be found here (https://quip-amazon.com/v0EZA6b2dcZm/Data-Mesh-CloudFormation-Template-Guide).

<br/>

## Resources 
Data Mesh PR/FAQ:
 https://quip-amazon.com/pDtpAXGUAeIf

Data Mesh Demo: https://amazon.awsapps.com/workdocs/index.html#/document/ac02173179a69f879dd56dcc2d6574955714970ad547752127215136ac8b05a2

<br/>

## References
https://aws.amazon.com/blogs/industries/how-data-mesh-technology-can-help-transform-risk-finance-and-treasury-functions-in-banks/

https://aws.amazon.com/blogs/big-data/integrating-aws-lake-formation-with-amazon-rds-for-sql-server/

https://aws.amazon.com/blogs/big-data/simplify-and-optimize-python-package-management-for-aws-glue-pyspark-jobs-with-aws-codeartifact/?nc1=b_rp

https://aws.amazon.com/blogs/big-data/build-a-modern-data-architecture-and-data-mesh-pattern-at-scale-using-aws-lake-formation-tag-based-access-control/

https://martinfowler.com/articles/data-monolith-to-mesh.html

