# aws-lambda-dot-net-core-sample
AWS Lambda is a serverless, event-driven compute service that allows users to run code without provisioning or managing servers. Users upload their code, and AWS automatically manages all the underlying infrastructure, scaling, and maintenance.

In this repo, I am trying to read the get the file from amazon s3 bucket and logging the content of file as an output.

## Additional ResourcesHow It Works

Upload Code: The developer packages and uploads their code as a ZIP file archive or container image to AWS Lambda.

Define Trigger: The developer sets up the function to be triggered by specific events from other AWS services or direct API calls.

Execution: When an event occurs, AWS Lambda automatically spins up an execution environment (a secure micro-VM via Firecracker), runs the function, and manages the necessary compute resources.

Billing and Termination: Once the code finishes running, the instance is terminated, and the user is billed only for the duration the code was active.
