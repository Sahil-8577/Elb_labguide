
### Exercise3: Create EC2 

For checking, Load Balancer is working properly or not we have to launch two instances in different subnets.

Follow the steps to launch the instances:

![](./images/ec2_1.png)

Search for the service ec2 and press Enter

![](./images/EC2_2.png)
Navigate to instances and click on Launch instances.

![](./images/ec2_3.png)
Give the unique name for ec2 instance.
Select the image.

![](./images/ec2_4.png)
choose the instance type and key pair.

![](./images/ec2_5.png)
(i) Select the vpc which you have created.
(ii) Select the subnet
(iii) Enable the public ip.

![](./images/ec2_6.png)
Add the security groups.

![](./images/ec2_7.png)
Add the above script so that we can see later that the traffic is routing to different subnet or not.

Now Launch one more ec2 in diff subnet.

![](./images/ec2_8.png)

You have Successfully created the two ec2 instances.
