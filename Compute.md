|If You Need To....	 | Customer Management Responsibilities | 	Deployment Unit	| Consider Using |
| :--- | :---: | :---: | ---: |
| Run any application. Control and manage server or cluster level functions such as scaling and deployment. |  You provision, scale, and manage server capacity. EC2 offers a wide selection of instance configurations optimized for every use case. You control the server, OS, and deployment software (if needed). You have flexible payment options to meet your business needs, including enabling BYOL. | Virtual Machines | Amazon EC2 |
| Run simple applications and websites on one or a few servers for a low, predictable price. | You follow instance creation experience to spin up a preconfigured virtual server in seconds. You don’t have to worry about security groups or other settings.You control the server, OS, and other software through the intuitive Lightsail console. But you have less control and fewer options available than EC2.You are billed a flat predictable rate for your plan each month. Plans start at $5. | Virtual Private Server (Instance) | Amazon Lightsail |




Run stateless or stateful applications packaged as Docker containers

| You provision and scale the server capacity and manage the utilization and availability.
AWS manages the fault tolerance of the application.
AWS manages cluster state and container deployment.
Containers	Amazon ECS
Run event-initiated, stateless applications that need quick response times

| AWS provisions and scales the server capacity and manages the utilization.
AWS manages the availability and fault tolerance of the application.
Code
AWS Lambda
