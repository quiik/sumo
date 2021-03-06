# Sumo Logic Observability

![IMG](images/sumo-logic-logo-vector.png)

<h3>Why is observability so important around distributed systems?</h3>

When you are builiding services within your appliactions that depend on other services that you may or maynot control. It is important to have visualization around those services. For instance how do you know if a service you control went down, how do you know if a service you don't control went down or how do you know if your appliaction has stopped functioning?

These are all things observability assist with. Giving you a visualization of what is happening inside your applicaiton. Building key SLI's around key componets that if down your applications stops functioning. 

![Architecture](images/diagram.png)

Above is my architecture of my current observability. I have two environements one on the east coast of the United States and the other on the west coast for disaster recovery. Even thought my architecture is around serverless components found in AWS I wanted to have a disaster recovery solution in case east-1 goes down unexpectedly again. 

<h4>Helpful Links:</h4>

[1]: <a href="https://help.sumologic.com/03Send-Data/Collect-from-Other-Data-Sources/Collect_AWS_Lambda_Logs_using_an_Extension" target="_blank">Sumo-Logic-Lambda-Configuration</a><br>
[2]: <a href="https://rakyll.medium.com/googles-approach-to-observability-frameworks-c89fc1f0e058 " target="_blank">Google-Approach-Observability</a>