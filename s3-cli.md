# AWS S3 - Simple Storage Service

###### This section provides the most frequent high-level S3 commands. Before typing any command you must have configured your AWS credentials and have AWS CLI installed.

List all S3 buckets
```shell
aws s3 ls
```

List all files and folders inside S3 buckets
```shell
aws s3 ls s3://<you-bucket-name>
```

Copy all files from /foo directory to bar bucket
```shell
aws s3 cp foo s3://bar --recursive
```

Copy all files from /foo directory to bar bucket excluding .mov files 
```shell
aws s3 cp foo s3://bar --recursive --exclude "*.jpg"
```
