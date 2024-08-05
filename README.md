# AWS-ELB
Hi everyone, as a part of my DevOps learning journey today I worked with ELB which stands for Elastic Load Balancer, it's a service provided by AWS for balancing the traffic flow of the clustered EC2 instances.

=>There are two load balancer ports:
 1. Frontend port (Listener)
 2. Backend port (Services on OS Listening)

Creating the load balancer for a healthcare website whose instances are spread across multiple zones.

1. Create an AMI of the EC2 instance.
2. Create a Template for AMI.
3. Use this template to launch multiple similar instances.
4. Create TargetGroup and add instances for health checks.
5. Create the LoadBalancer based on the requirements, I used an application load balancer to handle my HTTP requests.
