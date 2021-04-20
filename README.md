AWS IP Rotator
==============

Changes an EC2 machine's IP address every ten minutes using Elastic IP.

Requires the AWS CLI to be installed and valid AWS credentials configured:

    sudo apt update
    sudo apt install awscli
    aws configure


Usage
-----

Change your IP:

    ./aws-ip-rotator.sh

Start rotating IPs every ten minutes:

    ./aws-ip-rotator.sh start

Stop it:

    ./aws-ip-rotator.sh stop
