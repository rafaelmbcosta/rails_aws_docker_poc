Creating a instance

`aws ec2 run-instances --image-id ami-2b3b6041 --count 1 \
--instance-type t2.micro --iam-instance-profile Name=ecsInstanceRole \
--key-name aws-rafael --security-group-ids sg-0fdcc6e8cf55728e1 \
--user-data file://copy-ecs-config-to-s3`
