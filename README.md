#!/bin/bash
sudo yum -y update
sudo yum-y install ruby
sudo yum -y install wget
cd /home/ec2-user
wget http://aws-codedeploy-ap-south-1.s3.ap-south-1.amzonaws.com/latest
/install
sudo chmod +x./install
sudo ./install auto
sudo yum install -y python-pip
sudo pip install awscli
