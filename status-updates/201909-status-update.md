# Insight-ICON Monthly Progress Report 

Hello ICON Blockchain!  Insight Data Science here to give the first of the monthly status updates for our P-Rep Election campaign for ICON.  As many of you know, there is an election underway to find 22 qualified teams to for the decentralization network for the ICON Blockchain.  While we at Insight are mainly focused on tech, we are executing a broad strategy to grow the ICON ecosystem as a whole.  Here are some of the highlights. 

- Outreach Campaign 
    - Published [6] ICON focussed Medium articles 
    - Hosting weekly infrastructure calls 
    - Planning ICON events 
- Fellow Program + Staffing  
    - Allocated 3 DevOps fellows to ICON Infrastructure Projects  
    - [Hired fulltime DevOps engineer to build infrastructure]
- Technical 
    - Built one-click solution for deploying P-Rep and Citizen nodes 
    - Managing roughly 10k lines of infrastructure as code over 25 repositories 


## Outreach Campaign 

Writing code, while core to our mission with ICON, is only part of how we are growing the ecosystem.  Our Insight fellow program has a very large following on Medium where we are maintaining a steady stream of publications on ICON.  We are also hosting weekly infrastructure calls connect with other node operators in the community to strategize how we can build best practices that all can share.  And last, we are cooking up some events with Rhizome Capital and an SF Blockchain Week event in coordination with other teams. 

### Articles 

- [Medium How to vote for secure and stable cryptocurrency infrastructure](https://blog.insightdatascience.com/insight-icon-voting-f863b7323a25)
- [Infrastructure as Code for the ICON Blockchain](https://blog.insightdatascience.com/infrastructure-as-code-for-the-icon-blockchain-33fc1a056cf3)
- [ICON Blockchain Decentralization Delay](https://blog.insightdatascience.com/icon-blockchain-decentralization-delay-ceb0c8264fc0?source=friends_link&sk=398b3fcceb89e87b9fa6a73d84bd87d7)
- [ICON Blockchain Weekly Infrastructure Call #1 Recap](https://blog.insightdatascience.com/icon-blockchain-weekly-infrastructure-call-1-recap-a4efbc565914?source=friends_link&sk=5d12dbdd4695dfca4bc0269b130e36b3)
- [ICON Weekly Infrastructure Call #2/3 Recap](https://www.reddit.com/r/helloicon/comments/db3t5n/icon_weekly_infrastructure_call_23_recap/)

### Weekly Infrastructure Calls + YouTube Channel 

The community faces a common infrastructure challenge so Insight has began hosting weekly calls to coordinate efforts.  

taken the reigns in bringing the everyone together twice a week for infrastructure calls.  


### Events 

- [Rhizome Offline]()



## Fellows 

The greatest asset that Insight brings to the ICON ecosystem is our large fellow program that over 1000 highly skilled computer scientists and engineers will complete this year.  Prior to the last cohort of fellows starting, [a number of projects]() were proposed to the Silicon Valley DevOps fellows focusing on infrastructure related projects. Three fellows were then recruited and have been working for the past month on a [one-click deployment]() of ICON infrastructure.  Here is a brief overview of their work. 

### Security and Configuration Automation - [Soe San](https://www.linkedin.com/in/soe-san-win/)

Running P-Rep nodes necessitates a robust security standards and deployment platform.  This project focused on security hardening of nodes with Ansible and Packer all triggered by Terraform.  With this work in place, Insight is now using the best in class deployment tooling and able to stitch them together in a unified setting. 

### DDoS Prevention Configurations - [Stacy Alme](https://www.linkedin.com/in/stacyalme/)

Every public network is vulnerable to distributed denial of service.  This project is for building a layer of reverse proxy sentry nodes that limit traffic to sensitive ICON nodes and protect them from attacks.  Multiple different configurations of this protection layers are being built, tested, and integrated into our architecture. 

### Monitoring and Alerting Platform - [Richard Mah](https://www.linkedin.com/in/richardmah/) 

All nodes on ICON need to have a monitoring solution in place with alarms set up to alert node operators when events that need attention are unfolding.  This project was focused on building a services cluster with Kubernetes that runs a Prometheus monitoring stack with events such as high cpu usage and low disk space sending alarms via email, slack messages, and SMS text messages to node operators.  

Our fellows have done an amazing job with their projects so far.  Next month we'll include links to all their work and summary presentations.

### Full-time Hire - [Rob Cannon](https://www.linkedin.com/in/rob-cannon-21571317/)

Insight is excited to announce they have hired me, Rob Cannon, as an infrastructure architect & developer in residence.  In this role, I will be integrating the work from our fellow program into a unified reference architecture and package it up for distribution to the community.  Super excited to join the team and devote my time to ICON projects. 

## Technical 

The main value Insight brings to the ICON ecosystem is contributing high quality code where the pure volume of contributions speaks for itself.  Our work focuses on automating the deployment of the necessary infrastructure to run both P-Reps and Citizen nodes which will evolve into a broader DApps focussed suite of reference architectures.  We hope that with our work, application developers can go from ideation to production with minimal effort on setting up the required infrastructure. Here are some of the categories of tooling we are building. 

### One-Click Deployments 

In order to distribute our deployments to others, we build so called, "one-click" deployments which really translate to single scripts that deploy the whole infrastructure.  These scripts fire off modular sets of infrastructure as code that we can easily reconfigure to support a variety of network topologies. We have the first one 

### Modular Reference Architectures 





## Upcoming 

- 