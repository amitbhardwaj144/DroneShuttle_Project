# Welcome to the DroneShuttle Project Readme text, this is file is to give you a referrence on where to start, what to read.

# Architecture Design

Refer to the docs folder :
![DroneShuttles_ArchitectureDesign.drawio](/architecture/DroneShuttles_ArchitectureDesign.drawio.html)


## Documentation and Deployment Guide

Refer to the deployement guide :
![DroneShuttle_ProjectDeploymentGuide.pdf](/DroneShuttle_ProjectDeploymentGuide.pdf)


## Infrastructure-as-Code (IaC)

The templates below are included in this repository and reference architecture:

![DroneShuttles_Project]
        - [master.yaml]
            - [infrastructure/webapp-iam.yaml]
            - [infrastructure/webapp-s3bucket.yaml]
            - [infrastructure/webapp-vpc.yaml]
            - [infrastructure/webapp-securitygroup.yaml]
            - [infrastructure/webapp-rds.yaml]
            - [infrastructure/webapp-elb-appserver.yaml]
            - [infrastructure/webapp-autoscaling-appserver.yaml
            - [infrastructure/webapp-elb-webserver.yaml] 
            - [infrastructure/webapp-autoscaling-webserver.yaml]
            - [infrastructure/webapp-cdn.yaml]
            - [infrastructure/webapp-cloudwatch.yaml]
            - [infrastructure/webapp-route53.yaml]

More details about these template, please refer to deployement guide section.


## Author

Amit Bhardwaj

Copyright 2021 Amit Bhardwaj
