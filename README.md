# JMeter
### JMeter in a nutshell 


- What is JMeter


Apache JMeter is an Apache project that can be used as a load testing tool for analyzing and measuring the performance of a variety of services, with a focus on web applications. [Wiki]


- what is Load Testing? 

Applying Simulated load to a system and measure the overall impact on the system 


- What is Performance testing? 

Monitoring and measuring the performance of a system regardless of load. 


- Stress Testing? 

Subjecting the system to a load-based failure to be certain how and if that system recovers 


- Plugins

1- Plugins within JMeter allow you to extend the software beyond its orginal capabilites 


2- We can install plugins by moving <code> .jar </code> filesto the appropriate folder. 

3- Plugins are maintained by their respective author and are not necessarily the responsibility of Apache


We can searcch for plugins from this website:

 https://jmeter-plugins.org/

### Thread Group 

We can simulate users in our testing environemnt by using the <code> thread-group </code> in JMeter. Think of it as a group if people who are waiting in order to do what iswritten in the test plan. 


### Types of Thread-Group 

1- Startup Thread Group: Performs specified sctions only at the start of the load test


2- Thread Group: Acting as a group of users performing specific actions within the test plan. 


3- Shutdown Thread Group: Performs specified actions only at the end of the load test

In a nutshell, Thread groups


1- Act as users in the test

2- Perform actions specified in the test plan 


3- Can run at different times and be schedulded

4- Can run multiple thread groupsin one test. 

### Sampler

- Samplers are actiosn added to users 

- Can be simple or cmomplex depedning on the test 

There are many types of samplers (actions) such as


1- HTTP Sampler 

2- TCP Sampler

3- LDAP Request

4- JDBC Request

5- SMTP Sampler 

and many more 


### Listeners 

I can issue the actions in the load test, but I can't "hear" the reults. This is where listeners come in. 


Wat are listeners? 


- Help JMeter display information from test

- Show you what is going on 

- Only recommended for debugging/creating tests

- If used incorrectly, it will use a lot of the system resources. 

### Anatomy of a Test

1- Create a Test plan 

    inside a test plan, we have everything we need in order to perform a load test

    1-   