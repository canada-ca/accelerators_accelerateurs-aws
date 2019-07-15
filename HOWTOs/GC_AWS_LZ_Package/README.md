# GC Cloud Accelerator Landing Zone Deployment

The AWS Landing Zone provides a baseline multi-account architecture to centrally manage identity and access management, governance, data security, network design, and logging across the AWS cloud platform. 

Benefits include:
*	Automated - The solution includes templates to automate the creation of new AWS Account environments using AWS best practice and embedded security controls 
*	Scalable – Evolve the AWS infrastructure features and develop new service offerings for the Department as business requirements and cloud workload change
*	Guardrails not blockers – Templated immutable governance framework in each AWS Account provides centralized Security visibility and controls the blast-radius of security incidents
*	Auditable - Automatically sends logs to a secured central logging account enabling auditing and traceability across the entire AWS cloud platform

The AWS Landing Zone establishes a foundation for departments using AWS cloud services. The following figure depicts a generic landing zone environment and the provides a notional view of the controls that is delivered via the AWS component.

![LZ_Design_Pattern](https://github.com/canada-ca/accelerators_accelerateurs-aws/blob/master/HOWTOs/GC_AWS_LZ_Package/resources/aws-lz-design-pattern-example.png)

## Prerequisites

The following are pre-requisites that must be implemented prior to proceeding with the core build steps:
*	The solution is designed to be run in a brand new AWS account; 
*	The account must have a Service Limit increase for a minimum of 10 AWS accounts in AWS Organizations. It is also recommended to request a Service Limit increase for 50 AWS CloudFormation StackSets.; and 
*	Creation of a unique and valid email addresses in support of the establishment of the accounts that are created as part of the AWS Landing Zone deployment. This is outlined in the GC Accelerator Landing Zone Architecture document.

## GC Accelerator: AWS Landing Zone Package

The GC Accelerator package for AWS Landing Zone contains documents and automation scripts, including:
*	AWS Landing Zone Architecture – an overview of the AWS Landing Zone which is a baseline multi-account architecture to centrally manage identity and access management, governance, data security, network design, and logging across the AWS cloud platform.
*	AWS Landing Zone Detailed Topology – a detailed architecture view of the Core and an example User Account. 
*	AWS Landing Zone Core Build Book – a step-by-step build book of the Core services.
*	AWS Landing Zone User Account Build Book - a step-by-step build book when creating new User Accounts.
*	AWS Landing Zone Build Spreadsheet – a template to use while building the GC Accelerator – AWS Landing Zone Detailed Topology.
*	AWS Landing Zone PBMM Controls Mapping – a mapping of Customer Responsibilities that aligns the GC Security Control Profile for Protected B, Medium Integrity, Medium Availability (PBMM) with AWS services and features that can assist in meeting governance controls.

These documents are available on the GC/Code site available for GC Access Only at this time.
