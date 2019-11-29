# Purpose

This repo creates a AWS box with nginx.

# Pre-req

* Packer
* AWS account

# How to use this repo

* set up _aws_access_key_ and _aws_secret_access_key_ in the file located _$HOME/.aws/credentials_ on Linux and OS X as explained here https://www.packer.io/docs/builders/amazon.html
* run the following command to create the EC2 image `packer build templateaws.json`
