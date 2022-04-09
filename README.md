# Deploy-high-availability-web-app-AWS-CloudFormation
Features

    Create Stack with
        VPC
        Internet gateway
        4 subnets: 2 private and 2 public
        2 availability zones
        2 Nat gateways
        Routing Tables

    create server
        load balancer
        AutoScaling Group
        Launch Configuration

How to Run?

 run infrastructure

    ./create.sh stackname network-infra.yaml network-infra-params.json
 run server

    ./create.sh stackname server.yaml servers-infra-params.json
