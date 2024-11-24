## Lambda Layer Package Creator
# Purpose
Creates AWS Lambda layers by packaging Python dependencies from requirements.txt into the correct directory structure for AWS Lambda deployment.

# Usage
Place requirements.txt in same directory as script
Run: python lambda-deployment-package.py
Get layer.zip containing dependencies in python/lib/python3.12/site-packages/

# Requirements
Python 3.12
Windows: Requires pip with manylinux wheel support (standard)
Valid requirements.txt file for your desired AWS Lambda Function
Output
Creates layer.zip ready for AWS Lambda layer upload
Compatible with Amazon Linux runtime
