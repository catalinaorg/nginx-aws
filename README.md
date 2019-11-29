# Purpose

This repo creates a AWS box with nginx.

# Pre-req

* Packer
* AWS account

# How to use this repo

* set up aws_access_key and aws_secret_access_key in the file located $HOME/.aws/credentials on Linux and OS X as explained here https://www.packer.io/docs/builders/amazon.html
* run the followin command to create the EC2 image `packer build templateaws.json`
