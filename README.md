# webserver
AWS Webserver config

# Intro
Cloud foromation templated to create an AWS Webserver

# What it does
0. Creates an AWS Linux t2.nano webserver
1. Runs updates and installs Apache as well as a default webpage
2. Opens HTTP and HTTPS Security groups

# Improvements
0. HTTP Logging to cloudwatch so that you can debug HTTP or server issues
1. Cloud watch alerts
2. Signed HTTPS Cert so that there is no self-signed warning
3. Loadbalancer, Scaling group so that it can autoscale / scale dow
4. Docker Container so that redloying code is easier
5. User serverless so that it scales and saves money
6. Cloudformation creates AMI at end (using Lambda)
