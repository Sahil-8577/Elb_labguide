### Exercise2: Create two SUBNET
Now select **Subnets** from left panel and click ***create subnet*** present on top right.

![](./images/VPC16.png)</br>

Now Follow the steps as shown below</br>

i.Select VPC you have created for you subnet and Click create subnet</br>

![](./images/VPC18.png)</br>

![](./images/VPC19.png)</br>

In Subnet Settings,</br>

![](./images/VPC20.png)</br>
  i.Give unique name to your subnet</br>

  ii.Select the diff availbility zone for both the subnets.</br>

  iii.Select the IPv4 CIDR that you have created for VPC</br>

  iv.Now Give IPv4 CIDR for your subnet.</br>

![](./images/VPC21.png)</br>
Click on create Subnet and once you create the subnet 
successfully.</br>
create one more subnet in same vpc but in diff availbility zone.</br>

![](./images/VPC22.png)</br>

Now back to dashboard to see the subnets that is created.</br>

---
#### Creating Route Tables
Follow the steps for creating route table.</br>

![](./images/VPC23.png)</br>

select **Route Tables** from left panel and clik ***create Route Table*** present on top right.</br>

![](./images/VPC24.png)</br>
i.Give unique name to your Route table</br>

ii.Select the VPC you have created to associate it with route table.</br>

![](./images/VPC52.png)</br>
Click Create Route Table.</br>


![](./images/VPC25.png)</br>
Route Table created Successfully</br>
  
You will see the Route table in dashboard</br>
  
---
#### Creating Internet Gateway
Follow the steps for creating Internet Gateway.</br>

![](./images/VPC26.png)</br>
Select **Internet Gateway** from left panel and clik ***create Internet Gateway*** present on top right.</br>

![](./images/VPC27.png)</br>
(i) Give a unique name to your Internet gateway</br>
(ii) Click on Create Internet Gateway</br>
  
Once the creation is done attach *internet gateway* to VPC that you have created
Now Follow the steps as shown below:</br>

To Attach,</br>
  i.Click on Attach VPC on top right corner</br>

![](./images/VPC28.png)</br>

Select the VPC that you have created</br>

![](./images/VPC29.png)</br>

Clcik on attach Internet Gateway</br>

![](./images/VPC30.png)</br>
  
---
##### Edit Routes
Now back to **Route Table** and select **Routes** and perfom the action as shown</br>

Click Edit Routes</br>

![](./images/VPC33.png)</br>

Then Click Add Routes</br>

![](./images/VPC34.png)</br>

i. In destination select the item as shown in image.</br>

ii. In Target select *Internet gateway* and the internet gateway you have created.</br>

Click on *Save changes*</br>

![](./images/VPC35.png)</br>

##### Subnet Association
In **Route Table** select **Subnet Association** and perform the action as shown:</br>


![](./images/VPC31.png)</br>
Click Edit Subnet Association</br>


![](./images/VPC32.png)</br>

(i) Check mark the subnet .</br>
(ii) Click on *Save Association*.</br>

---
Now Again back to **your VPC** and select the VPC that you have created and panel that appears at bottom shows the ***Resource Map***</br>

![](./images/VPC40.png)

![](./images/VPC41.png)</br>
  
You have Successfully created the complete **VPC** with subnets,Route Table and Internet gateway which were not present before.
  
