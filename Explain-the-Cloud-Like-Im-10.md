# Explain the Cloud Like I'm 10

by Todd Hoff

* The **cloud** is a term that refers to computers in a data center over the internet.
* Origin is that we draw network diagrams and use a cloud icon to represent the internet.
* Cloud computing is the interest in studying what happens in this "cloud icon".
* Nothing magical. Everything happens in a data center with a bunch of cabinets containing servers that look like pizza-boxes. Although this varies from company to company.
* Cloud provider vs cloud service. Cloud service is an application that runs on the cloud that you can use to help get things done. Ex. Dropbox, OneDrive, Gmail, Facebook Messenger, Twitter, etc. Cloud provider allows you to rent computing in a data center. A cloud provider can also provide services which you can use to develop your own products such as a web, database, mail or messaging queueing service.
* Facebook Messenger is a cloud service. When you send a message using Facebook Messenger, the message is sent to a server in Facebook's data center. This message is then sent the person who it is intended for.
* Facebook has its own private cloud, hosting its services in its own data center. Facebook doesn't use a cloud provider. They are their own cloud provider. It makes more economical sense that way.
* Netflix is a contradiction, they use AWS, but they are more focused in building out and providing the cloud service rather than focusing too much developing the infrastructure. (Note this may be changing)
* Either above approach works. It depends on the company.
* Desktop application vs cloud application. Desktop application, boxed software, etc. data is stored locally on the computer. Sometimes only a single user can access at at ime. Cloud application, usually use a web browser. Data is stored remotely. Many users (as long as license permits) can access the application at the same time. 
* Internet is a series of interconnected networks. The networks individually, are connected by cables. Even using undersea cables.
* Cloud computing has gotten so popular that even AWS makes more money for Amazon than their online retail site.
* AWS S3 (Simple Storage System) was Amazon's first cloud service for storage. Then EC2 (Elastic Compute Cloud) brought computing as a service.
* EC2 is pay what you need. Then servers to host your application becomes an operational expensive rather than capital expenditure.
* Elastic computing - take more if you need, give back if you don't need it. Just get charged for what you use.
* All infrastructure work is offloaded to the cloud provider. This elimiantes the need to have to wait for IT department to install new hardware.
* Results in less staff needed. Developers also get hardware quick, which gives back more time to program.
* Software must also be coded to handle failures better. Software that can handle this and run under the assumption of being in the cloud is called "cloud native" software.
* Vendor lock-in is a risk. If you start out using AWS, you may be stuck using them in the future, and may not migrate to GCP for example, without a lot of work.
* IaaS - Infrastructure as a Service. These are services provided that relate ithcreating infrastcture. When renting a computer from EC2 or using storage from S3, that is using IaaS.
* IaaS usually is the lowest level of services a cloud provider can offer.
* PaaS - Platform as a Service. PaaS offerings must be a solid base on to build applications.
* PaaS is a set of high-level services developers can choose to build their applications from. CDN, firewalls, load balancing, DNS, etc.
* SaaS - Software as a Service. Full-blown software product. Not a service or product used to build some other product.
* IaaS, PaaS - used by develoers to build product. SaaS focuses on the end-user. 
* Applications don't get an entire physical computer to themselves. They get a VM.
* Real genius of the cloud: Selling previously unused computer capacity.
* Cloud computing succeeded because VMs allowed previously unused computer capacity to be repackaged and resold.
* Containers evolved from VM concept. Uses fewer resources. VM has to perform the job in looking like a full computer. So each VM gets a full copy of an OS. 
* With containers, the OS is shared. Programs are then isolated.
* Serverless - Update code (function) to a serverless service, and it can run on any environment. You don't have to worry about allocation or paying for unnecessary compute resources.

