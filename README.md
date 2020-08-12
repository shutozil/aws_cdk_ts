# aws_cdk_ts

## How to start server
```
$ docker-compose build
$ docker-compose up -d
$ docker exec -it ContainerID /bin/bash
```

## How to deploy
```
$ npm run build
$ cdk deploy -c vpc_id=VPC_ID -c key_pair=KEY -c cidr_ip=CIDR
```

## check module version
```
$ aws --version
$ cdk --version
```

## check profile
```
$ cat ~/.aws/config
```