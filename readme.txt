#!/bin/bash
#script  for login without ssh -i
echo "enter ip address"
read ip
ssh -i  task1.pem ec2-user@$ip


