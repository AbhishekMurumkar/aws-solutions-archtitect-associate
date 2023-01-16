# Elastic Network card

* A logical component that can be attached to an EC2 instance which helps to connect EC2 instance to internet
* These are mainly used to move over network traffic from one instance to another during failovers just by shifing this private IP from failed instance to an working instance, using ENI
* These created independently (not with creation of ec2 instances) and attached to them on the fly
* They are bound to AZ
* It can have 1 private IP and more than 1 secondary IP
* It can have 1 elastic IP
* It can have 1 public IP
* It can have 1 or more security groups
* It can have 1 MAC address
* The ENIs are created automatically when create an instance, thus are elimiated when we terminate the instance. The ENI that are created manually are kept even after instance deletion.

```
Hands - On : ENI : creation and attachment to ec2 instance
```