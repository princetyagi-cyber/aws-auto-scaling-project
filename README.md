# AWS Auto Scaling Project

## Objective

Automatically scale EC2 instances based on demand using AWS Auto Scaling.

---

## Services Used

- AWS EC2
- AWS Auto Scaling
- AWS Load Balancer
- Target Group
- CloudWatch

---

## Step 1 - Launch EC2 Instance

Launch a Red Hat EC2 instance.

![EC2](screenshots/ec2-instance.png)

---

## Step 2 - Create Launch Template

Create a launch template for Auto Scaling.

![Template](screenshots/launch-template.png)

---

## Step 3 - Create Target Group

Create a target group for EC2 instances.

![Target](screenshots/target-group.png)

---

## Step 4 - Create Application Load Balancer

Create an Application Load Balancer.

![ALB](screenshots/create-alb.png)

---

## Step 5 - Create Auto Scaling Group

Create an Auto Scaling Group.

![ASG](screenshots/create-asg.png)

---

## Step 6 - Configure Scaling Policy

Configure dynamic scaling policy.

![Policy](screenshots/scaling-policy.png)

---

## Step 7 - Test Auto Scaling Functionality

Increase CPU utilization and verify that Auto Scaling automatically launches additional EC2 instances based on the scaling policy.

![Output](screenshots/asg-output.png)

---

# Final Result

Successfully configured AWS Auto Scaling with Application Load Balancer and verified automatic instance scaling based on CPU utilization.
