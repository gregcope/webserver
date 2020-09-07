# webserver
AWS Webserver config

# Intro
Cloud foromation templated to create an AWS Webserver

# What it does
0. Creates an AWS Linux t3a.small webserver
1. Runs updates and installs Apache as well as a default webpage
2. Opens HTTP and HTTPS Security groups

# Improvements
0. Logging to cloudwatch so that you can debug HTTP or server issues
1. Cloud watch alerts for CPU/disk space
2. Signed HTTPS Cert so that there is no broswer warnings
3. Loadbalancer, Scaling group so that it can autoscale / scale down, split over AZs for reundancy
4. Docker Container so that redloying code is easier
5. User serverless so that it scales and saves lots of money
6. Cloudformation creates AMI at end (using Lambda)
7. Run updates on laptop beforehand and not lose your AWS MFA POTP or disconnect you landline
8. Use a nano instance type to save costs
9. DNS hostname/domain to match the TLS cert
10. Spot instance to save even more money ... OR reserved/prepay/savings plan
