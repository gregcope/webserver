# webserver
AWS Webserver config

# Intro
Cloud foromation templated to create an AWS Webserver

# What it does
1. Creates an AWS Linux t2.nano webserver
2. Runs updates and installs Apache as well as a default webpage
3. Opens HTTP and HTTPS Security groups

# Improvements
1. HTTP Logging to cloudformation so that you can debug HTTP or server issues
2. Signed HTTPS Cert so that there is no self-signed warning
3. Loadbalancer, Scaling group so that it can autoscale / scale dow
4. Docker Container so that redloying code is easier
5. User serverless so that it scales and saves money
