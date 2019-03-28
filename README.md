## Project

AWS ECR docker image cross-region replicator

## Requirements

* python3

## Dependencies

* boto3
* docker

## Installation 

pip3 install ecr2ecr

## Usage

ecr2ecr -s us-west-2 -d us-east-1 -n image-name -t latest


## Arguments

* -s --source-region      region where the image should be pulled from.
* -d --destination-region region where the image will be pushed to.
* -n --image-name         image:tag format
* -t --image-tag          image:tag format

## Author

@japzio

## Credits

TrustArc, Inc.

## License

Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/
https://opensource.org/licenses/Apache-2.0