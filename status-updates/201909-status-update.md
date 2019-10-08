# Insight-ICON Monthly Progress Report 

Hello ICON Blockchain!  Insight-ICON here to give the first of the monthly status updates for our P-Rep Election campaign for ICON.  As many of you know, there is an election underway to find 22 qualified teams to decentralize the validation network for the ICON Blockchain.  While we at Insight are mainly focused on tech, we are executing a broad strategy to grow the ICON ecosystem as a whole.  Here are some of the highlights. 

- Outreach Campaign 
    - Published 5 ICON focused Medium articles 
    - Hosting weekly infrastructure calls 
    - Planning ICON events 
- Fellow Program + Staffing  
    - Allocated 3 DevOps fellows to ICON Infrastructure Projects  
    - Hired fulltime DevOps engineer to build infrastructure
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

The community faces a common infrastructure challenge so Insight has began hosting weekly calls to coordinate efforts.  Each week we have recorded the meeting and [posted on YouTube](https://www.youtube.com/channel/UCMPrlANYbIrpfgtQZQ0w7kw?view_as=subscriber) along with a meeting summary that you can find on [Reddit](https://www.reddit.com/user/insight-icon) and our [blog](https://blog.insight-icon.net/blog/html/index.html).  We've been happy to collaborate with such teams as [iBriz](http://ibriz.ai/) and begin planning of docs with [Pocket / Figment](https://p-rep.community/pocket-figment/) and begin discussions with several other teams. 

### Events 

#### [Rhizome Offline](https://www.youtube.com/channel/UCTrh0D9A2KhEQ9DinSqakWQ)
On Friday, October 4th we were happy to have Rhizome's Brian Li interview us at our SF location where talked about our value add to ICON along with a high level overview of the tech we are working on right now.  Brian is editing the video as we speak and will send an update as soon as it is ready. 

#### [SF Blockchain Week]()

Insight is excited to host an open infrastructure party during SF Blockchain week on [Wednesday October 30th]() with workshops and interactive festivities at our [SF location](https://www.google.com/maps/place/500+3rd+St,+San+Francisco,+CA+94107/@37.7808204,-122.397855,17z/data=!3m1!4b1!4m5!3m4!1s0x80858078ccf4d77f:0xea8dde66a1b86f2!8m2!3d37.7808162!4d-122.3956663).  Stay tuned to our [twitter]() and [reddit]() to hear more details. 

## Fellows 

The greatest asset that Insight brings to the ICON ecosystem is our large fellow program that over 1000 highly skilled computer scientists and engineers will complete this year.  Prior to the last cohort of fellows starting, [a number of projects](https://docs.insight-icon.net/teams/insight/insight-icon-project-seeds/index-project-seeds.html) were proposed to the Silicon Valley DevOps fellows focusing on infrastructure related projects. Three fellows were then recruited and have been working for the past month on a [one-click deployment]() of ICON infrastructure.  Here is a brief overview of their work. 

### Security and Configuration Automation - [Soe San](https://www.linkedin.com/in/soe-san-win/)

Running P-Rep nodes necessitates a robust security standards and deployment platform.  This project focused on security hardening of nodes with Ansible and Packer all triggered by Terraform.  With this work in place, Insight is now using the best in class deployment tooling and able to stitch them together in a unified setting. 

### DDoS Prevention Configurations - [Stacy Alme](https://www.linkedin.com/in/stacyalme/)

Every public network is vulnerable to distributed denial of service.  This project is for building a layer of reverse proxy sentry nodes that limit traffic to sensitive ICON nodes and protect them from attacks.  Multiple different configurations of this protection layers are being built, tested, and integrated into our architecture. 

### Monitoring and Alerting Platform - [Richard Mah](https://www.linkedin.com/in/richardmah/) 

All nodes on ICON need to have a monitoring solution in place with alarms set up to alert node operators when events that need attention are unfolding.  This project was focused on building a services cluster with Kubernetes that runs a Prometheus monitoring stack with events such as high cpu usage and low disk space sending alarms via email, slack messages, and SMS text messages to node operators.  

Our fellows have done an amazing job with their projects so far.  Next month we'll include links to all their work and summary presentations.

### Full-time Hire - [Rob Cannon](https://www.linkedin.com/in/rob-cannon-21571317/)

Insight is excited to announce they have hired Rob Cannon (me), as an Infrastructure Architect & Developer in Residence.  I will continue to focus on engineering and operating our P-Rep node, hosting weekly infrastructure calls, and working closely with the Fellows to mentor their projects and integrate their ICON tools and imprevements into unified reference architecture. I'm super excited to join the team and devote my time to ICON projects. 

## Technical 

The main value Insight brings to the ICON ecosystem is contributing high quality code where the pure volume of contributions speaks for itself.   Our work is currently focused on automating the deployment of the necessary infrastructure to run both P-Reps and Citizen nodes in production and orchestrated testing environments.  This work, while key to running secure P-Rep nodes, will lay the foundation for our other core strengths of post-attack forensics (i.e. double signing protection) and DApp reference architectures.

Here is a brief highlight of some of our work or check it out at [github.com/insight-infrastructure](github.com/insight-infrastructure).
- 10k lines of Infrastructure as code
- 25 IaC repositories automated using tools such as Terraform, Ansible, and Packer 
- 3 supported network topologies for different levels of node operation 

### One-Click Deployments

In order to distribute our deployments to others, we build so called, "one-click" deployments which really translate to single scripts that deploy the whole infrastructure.  These scripts fire off modular sets of infrastructure as code that we can easily reconfigure to support a variety of network topologies. Check out first alpha out at [this link](). It uses Terraform and Ansible to deploy a P-Rep and Citizen node.  We're making some big changes this month and should be promoting it more in a couple weeks as we do a large code integration.  

## Summary 

That wraps up our monthly update.  Stay tuned for next month's update that will focus on how we integrated the work from our fellows into a unified architecture where we will give more details on the specific features that our deployment offers and guides on how to run it.  We are hoping to on-board several teams with our architecture over the coming month.
