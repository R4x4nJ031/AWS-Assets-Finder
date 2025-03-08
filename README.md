# AWS-Assets-Finder
Description

AWS Assets Finder is a Python tool that automates the enumeration of various AWS-related assets, including subdomains, S3 buckets, CloudFront distributions, EC2 instances, RDS databases, and IAM users. It leverages multiple tools to gather information efficiently.

Features

Subdomain Enumeration using Amass, Subfinder, and Assetfinder

S3 Bucket Enumeration using S3Scanner and AWS CLI

CloudFront Distribution Lookup using crt.sh and dig

EC2 Instance Scanning using Shodan and Censys

RDS Database Discovery using Nmap and Cloudbrute

IAM User Enumeration using Enumerate-IAM and AWS CLI

Multithreading for Faster Execution

Automatic Result Saving

Installation

Prerequisites

Ensure you have the following tools installed:

Python 3.x

amass, subfinder, assetfinder

s3scanner, aws-cli

jq, dig

shodan, censys

nmap, cloudbrute

enumerate-iam

Install dependencies if required:

pip install shodan censys

Usage

Run the script using Python:

python aws_enum.py

Enter the target domain when prompted.

Output

Results will be saved in a file named aws_enum_<domain>.txt.
