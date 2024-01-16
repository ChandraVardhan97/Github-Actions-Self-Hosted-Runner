## Github-Self-Hosted-Runner

- Create an EC2 instance with an Ubuntu AMI image. Open HTTP and HTTPS ports for inbound and outbound traffic for the necessary IP ranges.
- Add a self-hosted-runner in Github and configure the EC2 instance as the runner.
- Github Actions will start the workflow whenever there is push event. Here, we have a simple addition functionality and some unit tests for it. The same can be implemented for various other use cases.


