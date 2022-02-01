# Jenkins Deployment

## 1. Overview

This repository contains notes, documents, and code about how to deploy Jenkins. The deployment that's discussed here covers the following areas:

- The technical consideration, such as the choices of data storage, the operating system, the network solution.
- The security consideration.
- The technology that's used to deploy the Jenkins system, such as containers or Terraform.

## 2. Solution

## 3. Security Considerations

Do not use the built-in executors to build code. (TODO: Find the warning message.)

Do not allow outbound network traffic; only allow ingress traffic. See [1].

## 4. References

- [1] [Jenkins on AWS](https://d1.awsstatic.com/whitepapers/DevOps/Jenkins_on_AWS.pdf)