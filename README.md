# 👉Topics  ![Learn](https://img.shields.io/badge/Interview-Preparation-blueviolet?style=for-the-badge)

- [Topics !Learn](#topics-learn)
  - [DevOps Interview Questions](#devops-interview-questions)
  - [Programming:](#programming)
  - [OS-LINUX:](#os-linux)
  - [Networking:](#networking)
  - [Security:](#security)
  - [Docker](#docker)
  - [kubernetes](#kubernetes)
  - [Architecture:](#architecture)
  
********
## 👉DevOps Interview Questions


- Q1) Can you tell us the fundamental differences between DevOps & Agile?
  - A: Although DevOps shares some similarities with the Agile methodology, which is one of the most popular SDLC methodologies, both are fundamentally different approaches to software development. Following are the various fundamental differences between the two:

    - Agile Approach – The agile approach is only meant for development in Agile while the Devops approach is meant for both development and operations in DevOps.

    - Practices and Processes – While agile involves practices such as Agile Scrum and Agile Kanban, DevOps involves processes such as CD (Continuous Delivery), CI (Continuous Integration), and CT (Continuous Testing).

    - Priority – Agile prioritizes timeliness whereas, DevOps gives equal priority to timeliness and quality.

    - Release Cycles – DevOps offers smaller release cycles with immediate feedback while Agile offers only smaller release cycles without immediate feedback.

    - Feedback Source – Agile relies on feedback from customers while feedback from self (monitoring tools) is involved in DevOps.

    - Scope of Work – For Agile, the scope of work is agility only but for DevOps, it is agility and the need for automation.

- Q2) Why do we need DevOps?

  - A: Organizations these days are trying to transport small features to customers via a series of release trains instead of releasing big feature sets. There are several benefits of doing so, including better software quality and quick customer feedback.

  - All such benefits lead to a higher level of customer satisfaction, which is the most important goal for any product development project. To do so, companies need to:

      - Increase deployment frequency
      - Lessen lead time between fixes
      - Lower failure rate of new releases
      - In case of new release crashing, have a faster mean time to recovery

  - DevOps helps in fulfilling all these requirements and thus, achieving seamless software delivery. Full-fledged organizations like Amazon, Etsy, and Google have adopted DevOps methodology resulting in achieving performance levels that were previously uncharted.

  - With the adoption of DevOps methodology, organizations are able to accomplish tens to thousands of deployments in a single day. Moreover, doing so while offering first-rate reliability, security, and stability.

- Q3) What are the important business and technical benefits of using DevOps?

  - A: DevOps brings a lot of business and technical benefits to the table. Some of the most important ones are listed down as follows:

    - Business benefits:

      - Enhanced operating environment stability
      - Faster delivery of features
      - More time for adding value to the product

    - Technical benefits:

      - Continuous software delivery
      - Faster problem resolution
      - Lesser complex problems

- Q4) Can you name some of the most-used DevOps tools?

  - A: Following is a list of some of the most widely used DevOps tools:

      - Ansible – A configuration management and application deployment tool
      - Chef – A configuration management and application deployment tool
      - Docker – A containerization tool
      - Git – A version control system (VCS) tool
      - Jenkins – A continuous integration (CI) tool
      - Jira – An agile team collaboration tool
      - Nagios – A continuous monitoring tool
      - Puppet – A configuration management and application deployment tool
      - Selenium – A continuous testing (CT) tool

- Q5) What is Selenium used for?

  - A: Selenium is used for continuous testing in DevOps. The tool specializes in functional and regression forms of testing.

- Q6) What do you understand by Puppet in DevOps?
  
  - A: It is a configuration management tool that is used for automating administration tasks. Puppet makes use of the Master-Slave architecture in which the two entities communicate via an encrypted channel.

  - System admins need to perform a lot of repetitive tasks, notably installing and configuring servers. Writing scripts for automating such tasks is an option but it becomes hectic when the infrastructure is large. Configuration management is a great workaround for this.

  - Puppet helps in configuring, deploying, and managing servers. Not only does it make such redundant tasks easier but also cuts a significant portion of the total work time. The mature configuration management tool:

      - Continuously checks whether the needed configuration for a host is in place or not. If altered, the configuration is automatically reverted back
      - Defines distinct configurations for every host
      - Does dynamic scaling (up and down) of machines
      - Provides control over all the configured machines so that a centralized change can automatically get propagated to all of them

- Q7) What do you understand by anti-patterns of DevOps?
  
  - A: When a DevOps pattern commonly adopted by other organizations doesn’t work in a specific context and still the organization continues using it, it leads to the adoption of an anti-pattern. In other words, anti-patterns are myths about DevOps. Some of the notable anti-patterns are:

      - An organization needs to have a separate DevOps group
      - Agile equals DevOps
      - DevOps is a process
      - DevOps is development-driven release management
      - DevOps is not possible because the organization is unique
      - DevOps is not possible because the people available are unsuitable
      - DevOps means Developers Managing Production
      - DevOps will solve all problems
      - Failing to include all aspects of the organization in an ongoing DevOps transition
      - Not defining KPIs at the start of a DevOps transition
      - Reduce the silo-based isolation of development and operations with a new DevOps team that silos itself from other parts of the organization

- Q8) DevOps has something called CI. What is it and what is its purpose?
  - A: CI in DevOps stands for Continuous Integration. CI is a development practice in which developers integrate code into a shared repository multiple times in a single day.

    - Continuous Integration of development and testing enhances the quality of the software as well as reducing the total time required for delivery.

    - The developer has broken the build if a team member checking in code runs into a compilation failure. As such, other developers are not able to sync with the shared source code repository without introducing compilation errors into their own workspaces.

    - This disrupts the collaborative and shared development process. Hence, as soon as a CI build breaks, it’s important to identify and correct the problem immediately.

    - Typically, a CI process includes a suite of unit, integration, and regression tests that run each time the compilation succeeds. In case any of the aforesaid tests fail, the CI build is considered unstable (which is common during an Agile sprint when development is ongoing) and not broken.

- Q9) More often than not we hear shift left in DevOps. What is it?
  - A: The traditional software development lifecycle when graphed on a paper has two sides, left and right. While the left side of the graph includes design and development, the right side includes production staging, stress testing, and user acceptance.

  - To shift left in DevOps simply means the necessity of taking as many tasks on the right i.e. that typically happens toward the end of the application development process and incorporate them into earlier stages of a DevOps methodology.

    - There are several ways of accomplishing a shift left in DevOps, most notably:
    - Create production-ready artifacts at the end of every Agile sprint 
    - Incorporating static code analysis routines in every build

  - The level of doing the DevOps the right way is directly dependent on the degree of shifting left as much as possible.

- Q10) What does CAMS in DevOps stand for?
  - A: The acronym CAMS is usually used for describing the core creeds of DevOps methodology. It stands for:

   - Culture
   - Automation
   - Measurement
   - Sharing

- Q11) What are the several KPIs used to gauge DevOps success?
  - A: KPIs is a contracted form of Key Performance Indicators. In order to measure the success of a DevOps process, several KPIs can be used. Some of the most popular ones are:

   - Application performance
   - Application usage and traffic
   - The automated test pass percentage
   - Availability
   - Change volume
   - Customer tickets
   - Defect escape rate
   - Deployment frequency
   - Deployment time
   - Error rates
   - Failed deployments
   - Lead time
   - Meantime to detection (MTTD)
   - Mean time to recovery (MTTR)

- Q12) In your opinion, what are the major benefits of implementing DevOps automation?
  - A: Following are the major benefits of implementing DevOps automation:

    - Removal of the possibility of human error from the CD equation (Core benefit)

    - As tasks become more predictable and repeatable, it is easy to identify and correct when something goes wrong. Hence, it results in producing more reliable and robust systems

    - Removes bottlenecks from the CI pipeline. It results in increased deployment frequency and decreased number of failed deployments. Both of them are important DevOps KPIs

- Q13) What do you understand by containers?
  - A: Containers are a form of lightweight virtualization that help in providing isolation among processes. Containers are heavier than a chroot but lighter than a hypervisor.

- Q14) Microservices are a core part of DevOps. Can you name any two popular Java development frameworks for creating microservices?
  - A: There are several Java frameworks that allow creating microservices. However, Eclipse MicroProfile and Spring Boot stand out from the herd as the two leading Java development frameworks used in DevOps for creating microservices.

- Q15) What do you understand by a Version Control System (VCS)? Define its uses.
  - A: A Version Control System or VCS is a system that is capable of recording changes made to a file or a group of files over time. Git and Mercurial are two of the most popular version control systems. Important uses of a VCS are:

   - Check what was the last modification that caused a problem
   - Compare the changes made over time
   - Identifying who introduced a new issue and at what time
   - Revert a file or files to some earlier state
   - Revert the complete project to a previous state

- Q16) Git is a popular DevOps tool. Tell us how you will revert a commit that has already been pushed and made public.
  - A: There are two ways of doing so:

    - By creating a new commit to undo all changes made by the commit that has already been pushed and made public. Following command is used for doing so:
    - git revert

    - By fixing or removing the bad file in a new commit and then pushing it to the remote repository. After making necessary changes to the file, commit it to the remote repository using the command:
    - git commit -m “commit message”

- Q17) What are post mortem meetings?
  - A: Many times there is a need to discuss what went wrong during a DevOps process. For this, post mortem meetings are arranged. These meetings yield steps that should be taken to avoid the same failure or set of failures in the future for which the meeting was arranged in the first place.

- Q18) Draw a comparison between Asset Management and Configuration Management.
  - A: The process of monitoring as well as maintaining things of value to an entity or group is called an Asset Management.

  - Configuration Management refers to the process of controlling, identifying, planning for, and verifying the configuration items within service in support of Change Management.

- Q19) Can you state and explain various key elements of continuous testing?
  - A: Various key elements of continuous testing are:

      - Advanced analysis – Used for forecasting and predicting unknown future events
      - Policy analysis – Meant for improving the testing process
      - Requirement traceability – Refers to the ability to describe as well as follow the life of a requirement, from its origin to deployment
      - Risk assessment – The method or process of identifying hazards and risk factors that can cause potential damage
      - Service virtualization – Allows using virtual services instead of production services. Emulates software components for simple testing
      - Test optimization – Improve the overall testing process

- Q20) Please explain the core operations of DevOps in terms of development and infrastructure.
  - A: Core operations of DevOps in terms of development and infrastructure are:
  
      - Application development – Developing a product that is able to meet all customer requirements and offers a remarkable level of quality
      - Code coverage – Measurement of the total number of blocks or lines or arcs of the code executed while the automated tests are running
      - Code developing – Prepare the code base required for the product development
      - Configuration – Allowing the product to be used in an optimum way
      - Deployment – Installing the software to be used by the end-user
      - Orchestration – Arrangement of several automated tasks
      - Packaging – Activities involved when the release is ready for deployment
      - Provisioning – Ensuring that the infrastructure changes arrive just-in-time with the code that requires it
      - Unit testing – Meant for testing individual units or components

- Q21) What Do You Know about DevOps?

  - Your answer must be simple and straightforward. Begin by explaining the growing importance of DevOps in the IT industry. Discuss how such an approach aims to synergize the efforts of the development and operations teams to accelerate the delivery of software products, with a minimal failure rate. Include how DevOps is a value-added practice, where development and operations engineers join hands throughout the product or service lifecycle, right from the design stage to the point of deployment.


- Q22) Why Has DevOps Gained Prominence over the Last Few Years?

  - Before talking about the growing popularity of DevOps, discuss the current industry scenario. Begin with some examples of how big players such as Netflix and Facebook are investing in DevOps to automate and accelerate application deployment and how this has helped them grow their business. Using Facebook as an example, you would point to Facebook’s continuous deployment and code ownership models and how these have helped it scale up but ensure the quality of experience at the same time. Hundreds of lines of code are implemented without affecting quality, stability, and security.

  - Your next use case should be Netflix. This streaming and on-demand video company follow similar practices with fully automated processes and systems. Mention the user base of these two organizations: Facebook has 2 billion users while Netflix streams online content to more than 100 million users worldwide.

  - These are great examples of how DevOps can help organizations to ensure higher success rates for releases, reduce the lead time between bug fixes, streamline and continuous delivery through automation, and an overall reduction in manpower costs.

- Q23) Which Are Some of the Most Popular DevOps Tools? Do You Have Experience Working with Any of These Tools?

  - The more popular DevOps tools include:

     - Selenium
     - Puppet
     - Chef
     - Git
     - Jenkins
     - Ansible
     - Docker

- Q24) Do You Want to Master All These Devops Tools?

  - Thoroughly describe any tools that you are confident about, what it’s abilities are and why you prefer using it. For example, if you have expertise in Git, you would tell the interviewer that Git is a distributed Version Control System (VCS) tool that allows the user to track file changes and revert to specific changes when required. Discuss how Git’s distributed architecture gives it an added edge where developers make changes locally and can have the entire project history on their local Git repositories, which can be later shared with other team members.

- Q25) What Is Version Control and Why Should VCS Be Used?

  - Define version control and talk about how this system records any changes made to one or more files and saves them in a centralized repository. VCS tools will help you recall previous versions and perform the following:

  - Go through the changes made over a period of time and check what works versus what doesn’t.
    - Revert specific files or specific projects back to an older version.
    - Examine issues or errors that have occurred due to a particular change

  - Using VCS gives developers the flexibility to simultaneously work on a particular file and all modifications can be logically combined later.


- Q26) Is There a Difference Between Agile and DevOps? If Yes, Please Explain.

  - As a DevOps Engineer, interview questions like this are quite expected. Start by describing the obvious overlap between DevOps and Agile. Although the implementation of DevOps is always in sync with Agile methodologies, there is a clear difference between the two. The principles of Agile are associated with seamless production or development of a piece of software. On the other hand, DevOps deals with the development, followed by deployment of the software, ensuring faster turnaround time, minimum errors, and reliability.

- Q27) Why Are Configuration Management Processes and Tools Important?

  - Talk about multiple software builds, releases, revisions, and versions for each software or testware that is being developed. Move on to explain the need for storing and maintaining data, keeping track of development builds and simplified troubleshooting. Don’t forget to mention the key CM tools that can be used to achieve these objectives. Talk about how tools like Puppet, Ansible, and Chef help in automating software deployment and configuration on several servers.

- Q28) How Is Chef Used as a CM Tool?

  - The chef is considered to be one of the preferred industry-wide CM tools. Facebook migrated its infrastructure and backend IT to the Chef platform, for example. Explain how Chef helps you to avoid delays by automating processes. The scripts are written in Ruby. It can integrate with cloud-based platforms and configure new systems. It provides many libraries for infrastructure development that can later be deployed within a software. Thanks to its centralized management system, one Chef server is enough to be used as the center for deploying various policies.


- Q29) How Would You Explain the Concept of “Infrastructure as Code”(IaC)?

  - It is a good idea to talk about IaC as a concept, which is sometimes referred to as a programmable infrastructure, where infrastructure is perceived in the same way as any other code. Describe how the traditional approach to managing infrastructure is taking a back seat and how manual configurations, obsolete tools, and custom scripts are becoming less reliable. Next, accentuate the benefits of IaC and how changes to IT infrastructure can be implemented in a faster, safer and easier manner using IaC. Include the other benefits of IaC like applying regular unit testing and integration testing to infrastructure configurations, and maintaining up-to-date infrastructure documentation.

  - If you have completed a certification on Amazon Web Services (AWS), and are interviewing for niche roles such as AWS-certified DevOps engineer, here are some AWS DevOps interview questions that you must be prepared for:

- Q30) What Is the Role of AWS in DevOps?

  - When asked this question in an interview, get straight to the point by explaining that AWS is a cloud-based service provided by Amazon that ensures scalability through unlimited computing power and storage. AWS empowers IT enterprises to develop and deliver sophisticated products and deploy applications on the cloud. Some of its key services include Amazon CloudFront, Amazon SimpleDB, - - - Amazon Relational Database Service, and Amazon Elastic Computer Cloud. Discuss the various cloud platforms and emphasize any big data projects that you have handled in the past using cloud infrastructure.


- Q31) How Is IaC Implemented Using AWS?

  - Start by talking about the age-old mechanisms of writing commands onto script files and testing them in a separate environment before deployment and how this approach is being replaced by IaC. Similar to the codes written for other services, with the help of AWS, IaC allows developers to write, test, and maintain infrastructure entities in a descriptive manner, using formats such as JSON or YAML. This enables easier development and faster deployment of infrastructure changes.


- Q32) What are the success factors for Continuous Integration?
  - Examples of answers:
      - Maintain a code repository
      - Automate the build
      - Make the build self-testing
      - Everyone commits to the baseline every day
      - Every commit (to baseline) should be built
      - Keep the build fast
      - Test in a clone of the production environment
      - Make it easy to get the latest deliverables
      - Everyone can see the results of the latest build
      - Automate deployment

- Q33) How would you implement CI (continuous delivery) - end to end, including source control, branches, tools, etc. ?

- Q34) What is Continuous Delivery? Continuous Deployment?
  
- Q35) What is the difference between Continuous Integration, Continuous Delivery and Continuous Deployment?

- Q36) What is the difference between git and github ? What about git and SVN ?

- Q37) What is git rebase?

- Q38) In Git how do you revert a commit that has already been pushed and made public?

- Q39) What is puppet/chef/ansible used for? What are the advantages over shell scripts ?

- Q40) What do you understand by “Infrastructure as code”? How does it fit into the DevOps methodology? What purpose does it achieve?

- Q41) How do you give your developers access to the production logs ?

- Q42) Tell me about the worst-run/best-run outage you’ve been a part of. What made it bad/well-run?

- Q43) How do you monitor your application ? How do you make sure it is working ? How do you get alerts when it stops working ?

- Q44) What would be the availability and performance metrics for a key value store ? What about for MySQL replication ?

- Q45) How would you deploy software to 5000 systems?

- Q46) What is caching ? Where should a large scale application cache, and what data should be cached ?


************
## 👉Programming:

- Q1) What is your favorite scripting/programming language(s)? Why ?

- Q2) General CS, algorithms Q&A: 5 minutes

- Q3) Data structures - discuss possible implementations and applications:
    - Binary tree
    - Hash map
    - Heap

- Q4) Complexity classes - discuss and give examples:
  - Linear
  - Polynomial
  - NP Complete / NP Hard

- Q5) Sorting algorithms - discuss:
  - What is the fastest sorting algorithm?
  - What is the complexity of quick sort?

- Q6) Distributed systems:
    - What’s Paxos?
    - What's Raft?
    - What’s consistent hashing?

- Q7) Hands-on coding:
    - Inverse a string in place

- Q8) Deep Concept of DP and Graphs:

- Q9) Development Coding Questions.

- Q10) Describe a dev/test/production workflow using GIT
  - Feature branching vs trunk based development
  - Advantages of requiring pull requests and approvals
  


***********

## 👉OS-LINUX:

- Q1) How can you view running processes?
  - ps aux
  - top(htop)

- Q2) How do you check server uptime?
  - uptime
  - top

- Q3) How do you start/stop services?
  - (deprecated) service start/stop service_name
  - systemctl start/stop service_name

- Q4) How do you display the shell’s environment variables?
  - env
  - printenv

- Q5) What does #!/bin/bash at the top of a script do?
  - It say to shell, what interpreter to use when run this script

- Q6) What does "&" after a command do?
  - It run command in background

- Q7) What does piping commands mean?
  - piping with '|' transfer stdout of one command to another, for example,
  `ps aux | grep httpd` - first command show all running processes, then, transfer stdout to stdin of second command, whose find only strings where 'httpd'.

- Q8) What distributions have you used on servers?Why?
  - Ubuntu - very fresh kernels and packages
  - CentOS/RHEL - Enterprise and stability

- Q9) What is your favorite editor?

- Q10) What is RAID? What is RAID0, RAID1, RAID5, RAID10?

- Q11) Describe the general file system hierarchy of a Linux system.

- Q12) Describe what each of the following command line utilities do:
  - tee
  - awk
  - tr
  - cut
  - curl
  - tail
  - sed


- Q13)Command line demo:
  - Search for "my konfu is the best" in all *.py files
  - Replace the occurrence of "my konfu is the best" with "I'm a linux jedi master" in all *.txt files
  - Find all files which have been accessed within the last 30 days
  
- Q14) What is the difference between virtual memory and swap ?

- Q15) What is the difference between hardlinks and symlinks?

- Q16) What is an inode and what fields are stored in an inode?

- Q17) What are zombie processes ?

- Q18) Can you have several HTTPS virtual hosts sharing the same IP?
  - Yes, I can. I can setup several virtual hosts on one IP and split up yhem with different ports.

- Q19) What is the difference between processes and threads?

- Q20) What is the difference between exec and fork?

- Q21) How nginx can handle a lot of connections? What does it use inside?
  - Example of answer: Eventloop.

- Q22) What is "nohup" used for?

- Q23) What is an atomic operation?

- Q24) I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?

- Q25) How do you catch a SIGHUP ? What about SIGSEGV ? What about SIGKILL ?

- Q26) What is the Linux Kernel OOM and how does it work ?

- Q27) What's a chroot jail?

- Q28) Describe the Linux boot process with as much detail as possible, starting from when the system is powered on and ending when you get a prompt.

- Q29) What's LD_PRELOAD and when is it used?

- Q30) You ran a binary and nothing happened. How would you debug this?
  - I run binary with strace, for example: strace binary_name

- Q31) When can a socket receive E_AGAIN ?

- Q32) What is a dynamically/statically linked file?

- Q33) A careless sysadmin executes the following command: chmod 444 /bin/chmod - what do you do to fix this?

- Q34) I've lost my root password, what can I do?

- Q35) You have accidentally deleted a running script, how could you restore it ?

- Q36) What load balancers have you used ?

- Q37) AWS:
    - What is the difference between an AMI and an instance ?
    - What’s EBS ? What’s an EBS snapshot ? What is the real cost of having an EBS snapshot ?
    - What’s a VPC ?
    - What’s the difference between a region and an availability zone ?
    - What’s an ELB ?
    - What’s S3 ? What are the features supported on S3 ?


******************

## 👉Networking:

- Q1) What is IPv6 ? Why should we care?

- Q2) How does ping work ? What about traceroute ?

- Q3) I type http://www.yahoo.com in my browser’s URL bar and I press enter. What happens ? (discuss at every OSI layer - Physical, data link, network, transport, session, presentation, application)
    - DNS & anycast, IP, UDP, routing, BGP, TCP, HTTP, transparent proxy
    - What is BGP?
    - What’s a PTR in DNS? Why should we care?

- Q4) What if I change from http://www.yahoo.com to https://www.yahoo.com  ?
    - Public/private certificates, CAs, proxying, MiTM, etc.

- Q5) What happens when I press the send button in my email client ?

- Q6) How do we prevent bots crawling ? How would you deal with a syn flood ?

- Q7) How many hosts in a /24  network? What about a /22 ?

- Q8) What is the difference between DNAT and SNAT ? When do you use either ?

- Q9) What is a virtual IP address? What is a cluster?
  
- Q10) What is IPv6 ? Why should we care?




*******************

## 👉Security:


- Q1) What is the importance of SSL?
  - A: Using SSL ensure the security of the communication between server and client by encrypting the messages going bothways making sure even if the message are intercepted the attacker wouldn't be able to decrypt the messages.

- Q2) What is a SQL injection?
  - A: an attack that targets SQL database management systems by injecting SQL queries in a way that they are executed by the database. The goal is to manipulate the application's SQL query logic to gain unauthorized access to the database or retrieve, modify, or delete data.

- Q3) What is cross-site scripting (XSS)?
  - A: a web security vulnerability that allows attackers to inject malicious scripts into web pages viewed by other users. It occurs when a web application allows user input to be included in a web page without proper validation or escaping.
    - Stored XSS:
Malicious scripts are permanently stored on the target server, and every user who views the affected page is exposed to the attack.
    - Reflected XSS:
The injected script is reflected off a web server, such as in a URL, and executed immediately when the victim opens a manipulated link.
    
- Q4) Why shouldn’t you roll your own crypto?

- Q5) How are passwords stored on databases?

- Q6) What is a Man-in-the-middle attack?

- Q7) How do you safely manage environment variables in a cloud environment?

- Q8) How do you manage security updates?

- Q9) How do you keep encryption keys and credentials secure but make them available to machines that need them?


**********************


## 👉Docker

- Q1) What is docker used for?
- A: Docker is a tool that allows the creation, deletion, running and storing containers.

- Q2) How to show all containers on your system using docker?
  - A: `docker ps -a`

- Q3) How to delete an image that is already being used by a container?
  - A: `docker rmi -f`

- Q4) What command help you to delete all old unused images?
  - A: `docker image prune -f`

- Q5) What is docker-compose? What is docker-compose.yml?

- Q6) How to expose ports in docker-compose file?

- Q7) How to reduce docker images?
  - Using Multistage builds
  - using minimal base images
  - use as few layers as possible by reducing/combining Dockerfile commands  

- Q8) Where you  can store docker images?
  - A: using a container registry like AWS ECR

- Q9) What is alpine and why we need it?

*********************


##  👉kubernetes

- Q1) What is Kubernetes?
  - A: Kubernetes is an open-source container management tool that holds the responsibilities of container deployment, scaling & descaling of containers & load balancing. Being Google’s brainchild, it offers excellent community and works brilliantly with all the cloud providers. So, we can say that Kubernetes is not a containerization platform, but it is a multi-container management solution. 

- Q2) How is Kubernetes related to Docker?
  - A: It’s a known fact that Docker provides the lifecycle management of containers and a Docker image builds the runtime containers. But, since these individual containers have to communicate, Kubernetes is used. So, Docker builds the containers and these containers communicate with each other via Kubernetes. So, containers running on multiple hosts can be manually linked and orchestrated using Kubernetes.
  
- Q3) What is Container Orchestration?
  - A: Consider a scenario where you have 5-6 microservices for an application. Now, these microservices are put in individual containers, but won’t be able to communicate without container orchestration. So, as orchestration means the amalgamation of all instruments playing together in harmony in music, similarly container orchestration means all the services in individual containers working together to fulfill the needs of a single server.\

- Q4) What do you know about clusters in Kubernetes?
  - A: The fundamental behind Kubernetes is that we can enforce the desired state management, by which I mean that we can feed the cluster services of a specific configuration, and it will be up to the cluster services to go out and run that configuration in the infrastructure.
  So, as you can see in the above diagram, the deployment file will have all the configurations required to be fed into the cluster services. Now, the deployment file will be fed to the API and then it will be up to the cluster services to figure out how to schedule these pods in the environment and make sure that the right number of pods are running.

So, the API which sits in front of services, the worker nodes & the Kubelet process that the nodes run, all together make up the Kubernetes Cluster.

- Q5) How to do maintenance activity on the K8s node?
   - A: Whenever there are security patches available the Kubernetes administrator has to perform the maintenance task to apply the security patch to the running container in order to prevent it from vulnerability, which is often an unavoidable part of the administration. The following two commands are useful to safely drain the K8s node.

`kubectl cordon`
`kubectl drain –ignore-daemon set`
The first command moves the node to maintenance mode or makes the node unavailable, followed by kubectl drain which will finally discard the pod from the node. After the drain command is a success you can perform maintenance.

Note: If you wish to perform maintenance on a single pod following two commands can be issued in order:

`kubectl get nodes` to list all the nodes
`kubectl drain <node name>` drain a particular node
  
- Q6) What is the role of Load Balance in Kubernetes?
  - A: Load balancing is a way to distribute the incoming traffic into multiple backend servers, which is useful to ensure the application available to the users.
  In Kubernetes, as shown in the above figure all the incoming traffic lands to a single IP address on the load balancer which is a way to expose your service to outside the internet which routes the incoming traffic to a particular pod (via service) using an algorithm known as round-robin. Even if any pod goes down load balances are notified so that the traffic is not routed to that particular unavailable node. Thus load balancers in Kubernetes are responsible for distributing a set of tasks (incoming traffic) to the pods
  
- Q7) How to monitor the Kubernetes cluster?
  - A: Prometheus is used for Kubernetes monitoring. The Prometheus ecosystem consists of multiple components.

Mainly Prometheus server which scrapes and stores time-series data.
Client libraries for instrumenting application code.
Push gateway for supporting short-lived jobs.
Special-purpose exporters for services like StatsD, HAProxy, Graphite, etc.
An alert manager to handle alerts on various support tools

- Q8) Can you explain the differences between Docker Swarm and Kubernetes?
  - A: Below are the main difference between Kubernetes and Docker:

The installation procedure of the K8s is very complicated but if it is once installed then the cluster is robust. On the other hand, the Docker swarm installation process is very simple but the cluster is not at all robust.
Kubernetes can process the auto-scaling but the Docker swarm cannot process the auto-scaling of the pods based on incoming load.
Kubernetes is a full-fledged Framework. Since it maintains the cluster states more consistently so autoscaling is not as fast as Docker Swarm.
  
- Q9) How can containers within a pod communicate with each other?
  - A: Containers within a pod share networking space and can reach other on localhost. For instance, if you have two containers within a pod, a MySQL container running on port 3306, and a PHP container running on port 80, the PHP container could access the MySQL one through localhost:3306.
  
- Q10) Explain what is a Master Node and what component does it consist of?
  - A: The master node is the most vital component responsible for Kubernetes architecture
      It is the central controlling unit of Kubernetes and manages workload and communications across the clusters
      The master node has various components, each having its process. They are:
      -ETCD
      -Controller Manager
      -Scheduler
      -API Server
      
  - ETCD (Cluster store):
     -This component stores the configuration details and essential values
     -It communicates with all other components to receive the commands and work in order to perform an action
     -It also manages network rules and posts forwarding activity
    
  - Controller Manager
    -It is responsible for most of the controllers and performs a task
    -It is a daemon which runs in a continuous loop and is responsible for collecting and sending information to API server
    -The key controllers handle nodes, endpoints, etc.
  
  - Scheduler:
   -It is one of the key components of the master node associated with the distribution of workload
   -The scheduler is responsible for workload utilization and allocating pod to a new node
   -The scheduler should have an idea of the total resources available as well as resources allocated to existing workloads on each node
    

**********************


## 👉Architecture:

-1. Question: Explain the components of Kubernetes architecture and their roles.
Solution:
Kubernetes architecture consists of several key components:

Master Node: Manages the cluster and its components.
API Server: Exposes the Kubernetes API.
Controller Manager: Ensures the desired state of the cluster.
Scheduler: Assigns nodes to newly created pods.
etcd: Consistent and highly-available key-value store used as Kubernetes' backing store.
Node (Minion) Nodes: Where containers are launched.
Kubelet: Ensures that containers are running in a Pod.
Kube Proxy: Maintains network rules for Pod communication.
Container Runtime: Software responsible for running containers.

-2. Question: What is a Kubernetes Pod and how does it work in a cluster?
Solution:
A Pod is the smallest deployable unit in Kubernetes, representing a single instance of a running process in a cluster. Pods can contain multiple containers that share the same network namespace, allowing them to communicate with each other using localhost. Pods are scheduled to run on nodes and can be horizontally scaled by creating multiple replicas managed by Controllers like Deployments.

-3. Question: How does Kubernetes ensure high availability and fault tolerance?
Solution:
Kubernetes achieves high availability through:

Replication: Replicating applications across multiple nodes.
Self-healing: Automatically replaces failed containers or reschedules Pods.
Load Balancing: Distributes network traffic across multiple Pods.
Additionally, Kubernetes ensures fault tolerance through features like node monitoring, automatic scaling, and rolling updates, which allow applications to be updated without downtime.

-4. Question: Explain the concept of Kubernetes Services and their types.
Solution:
Kubernetes Services provide stable endpoints for Pods. There are several types of Services:

ClusterIP: Exposes the Service on a cluster-internal IP.
NodePort: Exposes the Service on each Node's IP at a static port.
LoadBalancer: Exposes the Service externally using a cloud provider's load balancer.
ExternalName: Maps the Service to the contents of the externalName field (e.g., a DNS name).

-5. Question: What are Kubernetes Deployments, and how do they manage application updates?
Solution:
Deployments in Kubernetes describe an application’s life cycle, enabling declarative updates for Pods and ReplicaSets. They provide a way to describe an application’s desired state. When a Deployment’s Pod template (e.g., container image version) is updated, it triggers a rolling update, ensuring zero-downtime updates. Old Pods are replaced by new ones gradually, minimizing disruptions.


# 👉Technical Questions [DevOps|System Administration|Mesosphere|Docker]

1. Have you worked with containers? What is a docker basically?

Docker container is an open source software development platform. Its main benefit is to package applications in “containers,” allowing them to be portable among any system running the Linux operating system (OS).

2. What is orchestration in cloud computing?

In most situations, cloud automation describes a task or function accomplished without human intervention. Cloud orchestration describes the arranging and coordination of automated tasks, ultimately resulting in a consolidated process or workflow. It is simplest to see this in an example.

3. What is Docker and what does it do?

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.
Docker provides this same capability without the overhead of a virtual machine. It lets you put your environment and configuration into code and deploy it. The same Docker configuration can also be used in a variety of environments. This decouples infrastructure requirements from the application environment.

4. Do you have any expreience with CI tools? Which ones?
Jenkins, Bamboo, TeamCity, etc.

5. Describe your experience implementing continuous deployment in a production environment
Answer should describe personal experience on types of jobs run, systems integrated, etc.

6. What function does DNS play on a network?
The DNS plays a critical role in supporting the Internet infrastructure by providing a distributed and fairly robust mechanism that resolves Internet host names into IP addresses and IP addresses back into host names.

7. What is HTTP?
The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems.[1] HTTP is the foundation of data communication for the World Wide Web.
Hypertext is structured text that uses logical links (hyperlinks) between nodes containing text. HTTP is the protocol to exchange or transfer hypertext.

8. What commands do you know that can be used to check DNS records?
$ host example.com
$ nslookup example.com
$ dig example.com

9. How to get all environment variables and how can you use them?
All UNIX-like operating systems such as OpenBSD, Linux, Redhat, CentOS, Debian allows you to set environment variables. When you log in on UNIX, your current shell (login shell) sets a unique working environment for you which is maintained until you log out.
printenv\env - command to print all or part of environment
Full command:
$ printenv PATH HOME
$PATH - Display lists directories the shell searches, for the commands.
$HOME - User's home directory to store files.

10. What is version control and why should version control system (VCS) be used?

Define version control and talk about how this system records any changes made to one or more files and saves them in a centralized repository. VCS tools will help you recall previous versions and perform the following:
Go through the changes made over a period of time and check what works versus what doesn’t.
Revert specific files or specific projects back to an older version.
Examine issues or errors that have occurred due to a particular change.
Using VCS gives developers the flexibility to simultaneously work on a particular file and all modifications can be logically combined later.

11. What is Docker hub?

Docker hub is a cloud-based registry service which allows you to link to code repositories, build your images and test them, stores manually pushed images, and links to Docker cloud so you can deploy images to your hosts. It provides a centralized resource for container image discovery, distribution and change management, user and team collaboration, and workflow automation throughout the development pipeline.

12. What is Dockerfile used for?

Dockerfile is nothing but a set of instructions that have to be passed on to Docker itself, so that it can build images automatically reading these instructions from that specified Dockerfile. A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.

13. Tell us how you have used Docker in your past position?

This is a question that you could bring upon your whole experience with Docker and if you have used any other Container technologies before Docker. You could also explain the ease that this technology has brought in the automation of the development to production lifecycle management. You can also discuss about any other integrations that you might have worked along with Docker such as Puppet, Chef or even the most popular of all technologies – Jenkins. If you do not have any experience with Docker itself but similar tools from this space, you could convey the same and also show in your interest towards learning this leading containerization technology.

14. How to create Docker container?

You can create a Docker container out of any specific Docker image of your choice and the same can be achieved using the command given below:
docker run -t -i command name
The command above will create the container and also starts it for you. In order to check whether the Docker container is created and whether it is running or not, you could make use of the following command. This command will list out all the Docker containers along with its statuses on the host that the Docker container runs.
docker ps -a

15. How to stop and restart the Docker container?

The following command can be used to stop a certain Docker container with the container id as

CONTAINER_ID:
docker stop CONTAINER_ID
The following command can be used to restart a certain Docker container with the container id as

CONTAINER_ID:
docker restart CONTAINER_ID

16.  How far do Docker containers scale?

Best examples in the Web deployments like Google, Twitter and best examples in the Platform Providers like Heroku, dotCloud run on Docker which can scale from the ranges of hundreds of thousands to millions of containers running in parallel, given the condition that the OS and the memory doesn’t run out from the hosts which runs all these innumerable containers hosting your applications.

17. What are the various states that a Docker container can be in at any given point in time?

There are four states that a Docker container can be in, at any given point in time. Those states are as given as follows:

• Running
• Paused
• Restarting
• Exited

19. Can you remove a paused container from Docker?

To answer this question blatantly, No, it is not possible to remove a container from Docker that is just paused. It is a must that a container should be in the stopped state, before it can be removed from the Docker container.

20. What is Mesos?

Mesos is a cluster manager that provides efficient resource isolation and sharing across distributed applications or frameworks. Mesos is a open source software originally developed at the University of California at Berkeley.

21. What is Marathon?
Marathon is a production-grade container orchestration platform for Mesosphere's Datacenter Operating System (DCOS) and Apache Mesos. 

22. What are the basic parameters you have to pass in a json file to orchestrate a service on Mesos via Marathon?
Bare minimum parameters would be service name, cpu, memory and application to deploy and the containerizer to be used.

23.  What is Git?
Git is a Distributed Version Control system (DVCS). It can track changes to a file and allows you to revert back to any particular change.

24. In Git how do you revert a commit that has already been pushed and made public?
It can be done in two ways:

By removing or fixing the bad file in a new commit and pushing it to the remote repository. Once the necessary changes to the file has been made, commit it to the remote repository. Use: git commit -m “commit message”

By creating a new commit that undoes all changes that were made in the bad commit. To do this, use command: git revert <name of bad commit>

25. What Is Ldap?

A GLDAP (Light-Weight Directory Access Protocol) determines how an object in an Active Directory should be named. LDAP is the industry standard directory access protocol, making Active Directory widely accessible to management and query applications. Active Directory supports LDAPv2 and LDAPv3.


26. According to an HTTP monitor, a website is down. You're able to telnet to the port, so how do you resolve the issue?

"Assuming the web page is up, I would investigate what could be wrong with the monitor. It could be a system overload or flapping, among other issues. Identifying the problem helps me prevent it in the future."

27. What are three attributes that make you a great systems engineer?
This question lends insight into candidates' self-awareness skills as well as whether their values match those of your business. Look for:

Answers that match areas of emphasis in your job description
At least one soft skill
Attributes that fit your company culture
"I'm analytical and curious. I always dig to find out why a problem occurred. Otherwise, it is liable to happen again and hurt the business. I am also a great communicator, able to share my insight with anyone in jargon-free language."

28. A Linux administrator wants to review the messages that scrolled up the screen during a system boot. How can this be accomplished?

The boot kernel messages are saved to the log file /var/log/dmesg. He can check this file.

29. Which utility could you use to repair the corrupted file system?

You can use fsck to repair the corrupted file system.

30. A user can not access a remote server. Which command he can use to verify that remote server is up and which command should he use to check if port 22 is open or closed?

He can use ping command to check whatever remote server is up or not and use the telnet command to check port accessibility.


# 👉Fun Questions

- What is your favorite side project?
- If you could learn any technology now, what would be?
- How do you keep up with current technology trends?
