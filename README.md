# Packer POC

Sample usage for [packer](https://www.packer.io/) by hashicorp 

# Before running
`AWS_ACCESS_KEY_ID='your_key'`

`AWS_SECRET_ACCESS_KEY='your_secret_key'`

Get packer installed.


--------------------------------------------
Image relies on existing VPC and SG - need to be customized when needed.
AMI will be created in eu-central-1

To build image run 
`packer build  custom-ami.json`
