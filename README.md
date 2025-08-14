# Launch-an-EC2-instance
# Project Summary: AWS EC2 Simulation
This project guides you through launching, configuring, monitoring, resizing, and terminating an Amazon EC2 instance. You’ll gain hands-on experience with core EC2 features, security groups, user data scripts, and AWS Systems Manager Fleet Manager. The simulation condenses real-world AWS workflows into a structured lab that can be completed in approximately 60 minutes.

# Objectives
- Launch an EC2 instance with termination protection enabled
- Deploy a simple web server via a user data script
- Monitor instance health and performance with CloudWatch and status checks
- Modify security group rules to allow HTTP access
- Connect to the instance using AWS Systems Manager Fleet Manager
- Stop, resize, and restart the instance with a different instance type
- Test and toggle termination protection
- Explore EC2 account limits

# Task Breakdow
 1  Launch EC2 Instance ( Configure Name tag, AMI, instance type, network settings, IAM role, and user data. ) 
 2  Monitor Your Instance ( Review system and instance status checks, view CloudWatch metrics, logs, and screenshot. ) 
 3  Update Security Group & Access Web Server ( Add HTTP inbound rule to security group and verify web server accessibility. ) 
 4  Connect via Fleet Manager ( Use Systems Manager Fleet Manager to establish a browser-based RDP session. ) 
 5  Resize Your Instance ( Stop the instance, change instance type to t2.nano, and restart to apply changes. ) 
 6  Test Termination Protection ( Attempt termination, disable protection, and successfully terminate the instance. ) 

# Core Concepts Covered
- Tagging and categorizing AWS resources with key–value pairs
- Amazon Machine Images (AMIs) and instance type selection
- Security groups as virtual firewalls for inbound and outbound traffic
- User data for automated instance configuration and software installation
- CloudWatch basic monitoring versus detailed monitoring options
- AWS Systems Manager Fleet Manager for remote instance management
- Lifecycle actions: stop, start, resize, protect, and terminate instances
- AWS EC2 service limits and best practices for resource management
