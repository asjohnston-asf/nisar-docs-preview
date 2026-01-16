# AWS S3 Access

## Overview
All NISAR data is hosted in the Amazon Web Services (AWS) cloud via the Simple Storage Service (S3). Data users can request temporary AWS credentials enabling direct access to the data in S3. This supports the use of a wide range of S3-aware tooling for interacting with cloud-hosted data as well as for low-latency and high-throughput data access patterns.

## Limitations

S3 Access for NISAR data is subject to several limitations:
- The temporary credentials expire after one hour.
- The temporary credentials only allow access from within the us-west-2 region

## Accessing NISAR Data via S3

