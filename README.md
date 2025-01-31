# python-aws-project
Python with AWS Lambda Project

Real World Problem
Lets assume a client drops many files into an S3 Bucket we own and they want to organize the files by day.

Solution
In this project we use Python and Lambda Functions to automate tasks in AWS. Specifically, we will create a Lambda Function that triggers when a file is added to an S3 bucket and moves it to a folder with the format YYYYMMDD/filename, based on the file's creation date.
