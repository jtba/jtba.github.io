## My Portfolio

Below you can find screenshots of applications I've created and code links to some of my personal projects. Many projects are still in early stages and some are experimental.

### Team Portal
**_All operation tasks in a single application_**

I'm lazy, but in a productive way. Disenchanted by the dozens of applications we had to perform our daily duties, I architected and developed a web application using Angular and PHP to bring everything my team needed, under a single UI. It features: 

* The ability to reset passwords across multiple application platforms (Tomcat, WebMethods, WebLogic, Oracle) spanning hundreds of servers in less than a minute
* Automatically collect application configuration for quick comparison across your entire cluster
* Central CMDB that allows the team to stay in control of their environment
* Create F5 I-Rules
* Track releases as they are occuring
* Suspend/Activate traffic to specific application instances

![image]({{ site.github.url }}/images/maaportal.png)
![image](https://github.com/jtba/jtba.github.io/blob/master/images/maaportal2.png)

### Praxis
**_Create/Deploy/Configure with a click of a button_**

Before DevOps was a thing, I developed an application with the goal of allowing any user to easily specify build templates via a GUI which is then handed to a PHP middleware that orchestrates the following:

* Creation of a Linux virtual machine by talking to VCenter
* Deployment of applications (Apache, Nginx, Tomcat, webMethods) utilizing Chef
* Creation of F5 VIP's, Pool's, and Members
* Configure applications via JSON

<img src="{{site.github.url}}/images/praxis.png"/>
![image](https://github.com/jtba/jtba.github.io/blob/master/images/praxis.png)
![image](https://github.com/jtba/jtba.github.io/blob/master/images/praxis1.png)
![image](https://github.com/jtba/jtba.github.io/blob/master/images/praxis2.png)
![image](https://github.com/jtba/jtba.github.io/blob/master/images/praxis3.png)

### Grafana Dashboards
**_The real power of these dashboards are the hand crafted API's using NodeJS_**

I've discovered quick wins by leveraging Grafana and ElasticSearch to graph timeseries data. This allowed for me to focus on creating several NodeJS services that integrate with the following technologies: 

* Oracle
* Teradata
* SOAP
* REST

![image](https://github.com/jtba/jtba.github.io/blob/master/images/dashboards.png)

### [Snowball](https://github.com/jtba/snowball)
**_Destroy your debt by using the snowball method_**

Still early in development, the Snowball application (soon to be known as Budget Co-Pilot) is being created to help individuals achieve zero debt by the following features:

* Track debt payoff progress
* Share your profile with a friend for accountability
* View payoff predictions by switching between different strategies
* Setup your own custom budget 

![image](https://github.com/jtba/jtba.github.io/blob/master/images/snowball.png)