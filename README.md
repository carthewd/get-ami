 # get-ami

Get AMI IDs for common AWS AMIs. Defaults to a statically defined 'latest' version but can be overriden. 

## Usage

Usage: get-ami <OS> [region]
Return the most recent AMI for a given operating system/distribution.
Examples:
get-ami rhel
get-ami rhel7.3

Supported arguments:
rhel/redhat
ubuntu
suse/sles
amzn
amzn2
windows

## Prerequisites
AWS CLI installed and configured with credentials - required permissions:
 - ec2:DescribeImages
 - ssm:GetParameter