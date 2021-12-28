# AWS_Infra-CFN
## Welcome to the DroneShuttle Project Readme text, this is file is to give you a referrence on where to start, what to read.

## Architecture Design

Refer to the docs folder :
[DroneShuttles_ArchitectureDesign.drawio](/architecture/DroneShuttles_ArchitectureDesign.drawio.html)


## Documentation and Deployment Guide

Refer to the deployement guide :
[DroneShuttle_ProjectDeploymentGuide.pdf](/DroneShuttle_ProjectDeploymentGuide.pdf)


## Infrastructure-as-Code (IaC)

The templates below are included in this repository and reference architecture:

[DroneShuttles_Project]

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

MIT License

Copyright (c) 2021 AmitBhardwaj144

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
