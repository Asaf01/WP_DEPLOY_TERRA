
Two-tier architecture, is a model of IT infrastructure that separates application components into two distinct layers: the presentation layer and the data layer.

    The presentation layer: also known as the front-end layer, is responsible for the user interface and interaction with end users. In the case of WordPress, this layer includes the web server that handles HTTP requests and displays website pages to visitors.

    The data layer: also known as the back-end layer, is responsible for data storage and access. For WordPress, this involves managing the database where articles, comments, user information, etc., are stored.


two EC2 instances connected to a load balancer. It is essential to ensure data consistency between the different EC2 instances that make up our architecture. This ensures that regardless of the instance selected by the load balancer, users will always see the same information without any inconsistency or data loss.

An effective way to guarantee this data consistency is to use Amazon Elastic File System (EFS) as a shared storage system for our EC2 instances in order to store the files of our WordPress site.



# WP_DEPLOY_TERRA![aws tier](https://github.com/Asaf01/WP_DEPLOY_TERRA/assets/123545280/397116ae-01ce-4e75-8447-4434d1095f15)
