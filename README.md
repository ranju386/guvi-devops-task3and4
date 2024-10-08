# guvi-devops-task3and4
network-tasks

Get me IP address of particular domain
![Get me IP address of particular domain](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task3-getip.jpg)

How do I find my CPU/memory usage of my server?
Giving Top Command and Giving Htop Command 
![CPU/memory usage](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task3-cpumemory.jpg)

Giving free -m (for memory usage in MB) and free -g (for memory usage in GB) command 
![free -m (for memory usage in MB) and free -g (for memory usage in GB)](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task3-cpu-freemomory.jpg)

Test the connectivity between 2 nodes?

Giving command ping guvi.in
![connectivity](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task3-connectivity.jpg)

I have deployed an application in guvi.com:9000, and logs shows my app is running, but I’m unable to view the page. Check whether my port is open or not ?

Giving nmap guvi.com
Port 80 open
Port 8080 open
Port 443 open

![nmap](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task4-nmap.jpg)

Command nmap -p 9000 guvi.com
Command nmap -p 9000 guvi.in
![command ](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task4-nmap-9000.jpg)

Command 
nmap -p 80 guvi.com    port 80 open
nmap -p 8080 guvi.com   port 8080 open
nmap -p 443 guvi.com   port 443 open
![nmap 80](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task4-nmap-80.jpg)

Command 
nmap -p 80 guvi.in    port 80 open
 nmap -p 8080 guvi.in   port 8080 open
nmap -p 443 guvi.in   port 443 open
![nmap 80 guvi.in](https://github.com/ranju386/guvi-devops-task3and4/blob/main/oct-devops-24-task4-nmap-80-guvi-in.jpg)

If your application is deployed on a cloud platform, ensure that the security group or network security settings allow inbound connections on port 9000.
Troubleshooting Application Deployment
Check Application Configuration:
Ensure that your application is correctly configured to listen on port 9000 and that the necessary services are running.
Network and DNS Configuration:

Verify that DNS settings are correct and that the network configuration allows traffic to reach your application server on port 9000.
By using these methods, you can determine whether port 9000 on guvi.com is open or not. If the port is closed or filtered, you may need to adjust firewall settings, network configurations, or troubleshoot your application deployment further.

