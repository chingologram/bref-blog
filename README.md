# Lumen Blog example on Bref POC

This is a sample proof-of-context of running the [Lumen microframework](https://lumen.laravel.com/) on [Bref](https://bref.sh/).

# Components

The project consists of a simple set of API endpoints that interact with an RDS MySQL instance in a VPC.
The example is based on the Serverless framework for easier configuration of the functions and resources.

# Deploying

- Install the Serverless framework.
- Clone the repository.
- Configure your SLS API key, or your AWS credentials directly via `aws configure`.
- Execute `sls deploy`.

