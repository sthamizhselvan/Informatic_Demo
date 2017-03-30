# quickstart-informatica-powercenter

This Quick Start deploys Informatica PowerCenter automatically into an AWS Cloud configuration of your choice. Informatica PowerCenter is a data integration solution that can process billions of records and connect to a vast array of data sources, including AWS services such as Amazon Simple Storage Service (Amazon S3), Amazon Relational Database Service (Amazon RDS), and Amazon Redshift.

![Quick Start Informatica PowerCenter Design Architecture](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/informatica-powercenter-architecture.jpg)

Deployment steps:

1. Sign up for an AWS account at http://aws.amazon.com, select a region, and create a key pair.
2. [Optional] Obtain a license for PowerCenter from [Informatica](https://now.informatica.com/di-powercenter-aws-contact-us.html).
3. In the AWS CloudFormation console, launch one of the following templates from the S3 URL to build a new stack:
  * [informatica-powercenter-master.template](https://s3.amazonaws.com/quickstart-reference/informatica/powercenter/latest/templates/informatica-powercenter-master.template) (to deploy Informatica PowerCenter into a new VPC)
  * [informatica-powercenter.template](https://s3.amazonaws.com/quickstart-reference/informatica/powercenter/latest/templates/informatica-powercenter.template) (to deploy Informatica PowerCenter into your existing VPC)

To customize your deployment, you can choose different instance types for your resources and configure the size of the Informatica embedded cluster. You can also choose to import sample catalog data to start using Enterprise Information Catalog on AWS.

For detailed deployment and configuration instructions, see the [Quick Start deployment guide](https://s3.amazonaws.com/quickstart-reference/informatica/powercenter/latest/doc/informatica-powercenter-on-the-aws-cloud.pdf).
