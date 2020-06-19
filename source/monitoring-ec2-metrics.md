# Part one: Monitoring EC2 metrics

EC2 stands for Elastic Cloud Compute, and it is the AWS service used for provisioning virtual compute resources.

EC2 can be used for availing compute resources like vCPUs, vRAMs and additional storage can be attached with these instances. EC2 instances come pre-installed with the server OS of different kinds. A Cloud Consumer can provision these resources over cloud and then access the instance remotely from either:

1. A web-based CLI tool
2. A native CLI tool using SSH key pairs

<!--Write about EC2 metrics-->
For the purpose of this project I have used the second kind.

## 1.1 Configuring EC2 instance over AWS Cloud console

### Step 1: Choosing AMI (Amazon Machine Image)
![](.././assets/choosing-ami-1.png)

### Step 2: Choosing Instance type
![](.././assets/choosing-instance-type-1.png)

### Step 3: Configuring Instance details
![](.././assets/configuring-instance-details.png)

### Step 4: Creating new key pair
![](.././assets/creating-new-key-pair.png)


## 1.2 Connecting to instance

Using the **new-key-pair** file generated and downloaded, a native CLI instance can be connected to an EC2 instance.

![](.././assets/connecting-to-ubuntu-instance.png)

## 1.4 Working on the EC2 instance

![](.././assets/work-on-instance-1.png)
![](.././assets/work-on-instance-2.png)
![](.././assets/work-on-instance-2_2.png)
![](.././assets/work-on-instance-3.png)

## 1.5 Monitoring Metrics in AWS CloudWatch dashboard

### Step 0: (Optional) Enabling detailed monitoring
![](.././assets/cloud-watch-detailed-monitoring.png)

### Step 1: Observe initial metric values
![](.././assets/cloud-watch-monitoring-init.png)
![](.././assets/cloud-watch-monitoring-ni.png)
![](.././assets/cloud-watch-monitoring-no.png)
![](.././assets/cloud-watch-monitoring-npi.png)

### Step 2: Observe final metric values
![](.././assets/cloud-watch-monitoring-ni-final.png)
![](.././assets/cloud-watch-monitoring-no-final.png)
![](.././assets/cloud-watch-monitoring-npi-final.png)

### Step 3: Observe metrics collectively and relatively over CloudWatch dashboards

![](.././assets/cloud-watch-graph-init.png)
![](.././assets/cloud-watch-graph-no-ni.png)
![](.././assets/cloud-watch-graph-no-ni-dwo.png)
![](.././assets/cloud-watch-graph-no-ni-dwo-dwb.png)
![](.././assets/cloud-watch-graph-all.png)
