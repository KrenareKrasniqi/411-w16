# 411-w16
This project includes performance Measures in Telecommunications 

Data transfer performance measure using "time" command
We had to organise the experiment on two different scales:
  copy files with specified size to another folder in the same system 
  copy files with specified size to another system over the network using "nc" tool and two distinguished protocols: UDP and TCP

To capture the traffic with more information we use the command: tcpdump -i eth0 -c 5 -ttt

