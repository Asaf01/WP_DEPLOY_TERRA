
Two-tier architecture, is a model of IT infrastructure that separates application components into two distinct layers: the presentation layer and the data layer.
EC2 instances connected to a load balancer. It is essential to ensure data consistency between the different EC2 instances that make up our architecture. This ensures that regardless of the instance selected by the load balancer, users will always see the same information without any inconsistency or data loss.

An effective way to guarantee this data consistency is to use Amazon Elastic File System (EFS) as a shared storage system for our EC2 instances in order to store the files of our WordPress site.


![2019-02-13_00-55-39-826ea8db5a1179c5f79d02b3b6cf1f2c](https://github.com/user-attachments/assets/b20cfd02-de9d-44b8-bdb9-d47aaa913fce)



# WP_DEPLOY_TERRA![aws tier](https://github.com/Asaf01/WP_DEPLOY_TERRA/assets/123545280/397116ae-01ce-4e75-8447-4434d1095f15)
