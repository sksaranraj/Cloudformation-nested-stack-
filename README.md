# Cloudformation-nested-stack

1. The repo contains 3 Yaml files
2. The SG and VPC are the two yaml files which will create Security group and vpc
3. We are creating one main.yaml file, which will import these above two files and pass the value of VPCID to the SG.

