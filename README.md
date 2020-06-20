# AWS CloudWatch Demonstration

<pre>    ___        ______  
   / \ \      / / ___| 
  / _ \ \ /\ / /\___ \ 
 / ___ \ V  V /  ___) |
/_/   \_\_/\_/  |____/ 
                       
  ____ _                 ___        __    _       _     
 / ___| | ___  _   _  __| \ \      / /_ _| |_ ___| |__  
| |   | |/ _ \| | | |/ _` |\ \ /\ / / _` | __/ __| &apos;_ \ 
| |___| | (_) | |_| | (_| | \ V  V / (_| | || (__| | | |
 \____|_|\___/ \__,_|\__,_|  \_/\_/ \__,_|\__\___|_| |_|
                                                        
     _                      
  __| | ___ _ __ ___   ___  
 / _` |/ _ \ &apos;_ ` _ \ / _ \ 
| (_| |  __/ | | | | | (_) |
 \__,_|\___|_| |_| |_|\___/ 
</pre>

This is AWS CloudWatch demonstration which is also my mini project for the fourth semester January-July 2020.

---
Problem Statement: "Demonstrate the use of Amazon CloudWatch to collect and track all metrics, collect and monitor log files, set alarms, and automatically react to changes in your AWS resources."
---

## Project division

According to the problem statement, this project is divided into three parts:

1. [Monitoring (tracking) metrics using CloudWatch](./source/monitoring-ec2-metrics.md)
2. [Setting and monitoring log files over CloudWatch](./source/monitoring-ec2-logs.md)
3. [Setting Alarms in the CloudWatch console](./source/setting-alarms.md)

## Technical requirements

This demonstration was set up on Amazon Web Services console. Howecer, in order to access the VM, native CLI and openssh were used on Ubuntu 18.04.

Following are the AWS provided technologies used for this demo:

- CloudWatch
- EC2
- IAM
- awslogs


