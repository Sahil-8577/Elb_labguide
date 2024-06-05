
### Exercise3: Create EC2 

For checking, Load Balancer is working properly or not we have to launch two instances in different subnets.

Follow the steps to launch the instances:

![](./images/ec2_1.png)

Search for the service ec2 and press enter</br>

![](./images/EC2_2.png)</br>
Navigate to instances and click on Launch instances.</br>

![](./images/ec2_3.png)</br>
Give the unique name for ec2 instance.</br>
Select the image.</br>

![](./images/ec2_4.png)</br>
choose the instance type and key pair.</br>

![](./images/ec2_5.png)</br>
(i) Select the vpc which you have created.</br>
(ii) Select the subnet</br>
(iii) Enable the public ip.</br>

![](./images/ec2_6.png)</br>
Add the security groups.</br>

![](./images/ec2_7.png)</br>
Add the above script so that we can see later that the traffic is routing to different subnet or not.</br>

Now Launch one more ec2 in diff subnet.</br>

![](./images/ec2_8.png)</br>

You have Successfully created the two ec2 instances.
