# 411-w16
This project includes performance Measures in Telecommunications 

To create the files has been used this command:

(example) dd if=/dev/zero of=1M.dat count=1024 bs=1024

Then, to copy the files with a specified size we used the nc command.
We had to organise the experiment on two different scales:
  copy files with specified size to another folder in the same system 
  copy files with specified size to another system over the network using "nc" tool and two distinguished protocols: UDP and TCP

To capture the traffic with more information we use the command: tcpdump -i eth0 -c 5 -ttt

