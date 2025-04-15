# VPC Infrastructure

## Description
CloudFormation template for creation of VPC infrastructure

## Usage
CloudFormation templates should be committed to the following branches:
- 'dev' for the Development account
- 'prod' for the Production account
- 'infra' for the Infrastructure account
- 'art' for the Artifacts account
- 'work' for the Workloads account

The CloudFormation template code should be stored in the 'infra' folder in the 'cf.yaml. file; parameters can be stored in the cf_parameters.json file

To deploy the resources use the 'create_infra.sh' script stored in the 'cloudformation' directory of the Aws_account_tools repository
