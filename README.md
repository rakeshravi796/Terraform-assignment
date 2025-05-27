<h1>Architecture that was created</h1>

<p>We are using aws as the provider and initialized in main.tf file</p>
<p> We are creating Virtual Pricvate cloud with 2 private subnets and 2 public subnet and has a internet gateway outside world to communicate with our vpc.</p>
<p>A route table has been created and is being associated with our public subnets</p>
<p>We have created security group for the automatic load balancers and the ec2 instances </p>
<p>We are creating EC2 instances with 2 ebs volumes too</p>
<p>We are also creating alb and creating target groups and attaching them to it and load balancer listener at port 80 for incoming requests.</p>
