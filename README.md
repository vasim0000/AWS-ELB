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

![Screenshot (174)](https://github.com/user-attachments/assets/77b9905a-5d23-4879-8f23-99effdce9daa)
![Screenshot (175)](https://github.com/user-attachments/assets/e5341048-6f23-40fb-a080-52d2b489f557)
![Screenshot (177)](https://github.com/user-attachments/assets/f8f54ec5-e039-4835-86de-f74b568d758f)
![Screenshot (178)](https://github.com/user-attachments/assets/813b02ff-c84d-4e94-874e-14b342d6f5ff)
![Screenshot (179)](https://github.com/user-attachments/assets/2c37cd46-d878-4873-9c02-eb860d95d38d)
![Screenshot (180)](https://github.com/user-attachments/assets/82ceee57-7428-41a4-87a4-4e1774da6c7e)






