# AZURE_AUTOSCALING

Title: Azure AutoScaling with Virtual Machine Scale Sets

![image](https://github.com/21a91a6121/AZURE_AUTOSCALING/assets/98638809/21b1e78e-fb47-4f0b-9463-ccf7ba0358b4)


Introduction:
This project showcases the power of Azure technology by implementing auto-scaling for virtual machines using Virtual Machine Scale Sets. Through the Azure Portal, we created a dynamic environment capable of automatically adjusting the number of instances based on CPU usage. This project provides a comprehensive guide on scaling, alerting, and monitoring, which is invaluable for optimizing system performance.

Creating a Virtual Machine Scale Set:
Our journey began by setting up a Virtual Machine Scale Set, a flexible solution for managing a group of identical virtual machines. During the configuration, we specified the total number of instances to be created and the incremental number to be added each time. Furthermore, we defined a crucial parameter: the CPU usage percentage at which a new instance should be spun up.

Setting Up Alerts and Notifications:
To keep an eye on our auto-scaling system, we established an action group, which allows us to define how notifications are handled. Within this action group, we created an alert rule that triggers notifications through various channels such as email, phone number, or the Azure mobile app. This alerts us when certain CPU usage thresholds are reached, ensuring we stay informed and can take action as needed.

Monitoring CPU Usage:
We leveraged Azure Monitor to monitor and visualize the CPU usage of our virtual machines. Through an intuitive dashboard, we observed real-time graphs and statistics, which allowed us to understand how our auto-scaling system responded to varying workloads. This monitoring is invaluable for making data-driven decisions and optimizing the performance of our virtual machines.

Optimizing System Performance:
In conclusion, this project offers a comprehensive guide to implement auto-scaling with Virtual Machine Scale Sets in Azure. With the ability to dynamically adjust resources based on CPU usage and receive real-time alerts, this solution ensures system performance optimization while keeping costs in check. It's an essential resource for anyone looking to manage resources efficiently in a cloud environment.
