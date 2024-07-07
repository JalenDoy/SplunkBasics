# SplunkBasics
<p align="center">
<br/>
<img src="https://i.imgur.com/d7rHJaa.png"/>

<h2>Description</h2>

Splunk is one of the leading SIEM solutions in the market that provides the ability to collect, analyze and correlate the network and machine logs in real-time. In this room, we will explore the basics of Splunk and its functionalities and how it provides better visibility of network activities and help in speeding up the detection.

<h2>Task 1: Introduction</h2>

<h2>Learning Objective and Pre-requisites</h2>

If you are new to SIEM, please complete the Introduction to SIEM. This room covers the following learning objectives:

 - Splunk overview
 - Splunk components and how they work
 - Different ways to ingest logs
 - Normalization of logs

<h2>Task 2: Connect with the Lab</h2>

Before moving forward, deploy the machine. When you deploy the machine, it will be assigned an IP. Access this room in a web browser on the AttackBox, or via the VPN at http://MACHINE_IP. The machine will take up to 3-5 minutes to start.

<p align="center">
<br/>
<img src="https://i.imgur.com/BXEqKgw.png"/>

<h2>Task 3: Splunk Components</h2>

Question 1:  **Which Component is used to collect and send data over the splunk instance?** Forwarder

<h2>Task 4: Navigating Splunk</h2>

Question 1:  **In the Add Data tab, which option is used to collect data from files and ports?** Monitor

<p align="center">
<br/>
<img src="https://i.imgur.com/Wp6kgey.png"/>

<h2>Task 5: Adding Data</h2>

Instructions: Download the TryHackMe VPN logs and upload them to the Splunk instance. Create a new index called VPN_Logs and complete the following questions. 

<p align="center">
<br/>
<img src="https://i.imgur.com/yYFZkNd.png"/>

Question 1:  **Upload the data attached to this task and create an index "VPN_Logs". How many events are present in the log file?** 2862. 

Question 2:  **How many log events by the user Maleena are captured?** 60. 

Hint: Type UserName="Maleena" in the search field.

Question 3:  **What is the name associated with IP 107.14.182.38?** Smith. 

Question 4:  **What is the number of events that originated from all countries except France?** 2814. 

Question 5:  **How many VPN Events were observed by the IP 107.3.206.58?** 14.

Hint: Type Source_ip="107.3.206.58" in the search field.


<h2>Task 5: Conclusion</h2>

In this room, we explored Splunk, its components, and how it works
