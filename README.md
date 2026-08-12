# Production Cloud Platform

## Project Goal
- Creating a terraform managed aws platform which will host a containerised HTTP application. Also trying to implement best practises in cloud infrastructure management and trying to implement failure and recovery testing.

## Requirements
- The application must be accessible from the public internet over HTTPS.
- The application workload must run as a container.
- Infrastructure must be provisioned and managed through Terraform.
- The application compute should not be directly exposed to the public internet.
- AWS permissions should follow least-privilege principles.
- Application and infrastructure logs and metrics must be available for troubleshooting.
- The platform should avoid unnecessary AWS costs and include basic cost controls.
- The deployment should be reproducible from the repository.
- The platform should support deliberate failure and recovery testing.

## Current Status

- Project definition and architecture planning.