# firewall-testing
cyber security internship at elevate labs
# Firewall 
The firewall is flitering network traffic and monitoring in & out traffic.It is total based on rules a with signatures.

Firewall is present inside and outside organzations.The firewall have basically two types of detection.

They are : Intrusion Detection System(IDS)

Intrusion Prevention System(IPS)

IDS : It works for detection security measures.It means detecting traffic with rules and signature bases.

IPS : It works for blocking incidents with rules and signatures.

# UFW Firewall with GUI Interface
The UFW stands for Uncomplicated FireWall.It meas friendly interface makes user easier.It kali linux firewall to install run command.

          sudo apt install gufw -y

<img width="1880" height="815" alt="Nessus scanners-output-img" src="https://github.com/CharanCSE02/Task-4-Firewall-testing/blob/main/Screenshot 2025-09-28 221151.png" />

# Telnet
The telnet is used remote connections and interaction.It means we connect to ip address,Domain etc.In port of 23.

Example:It gather some infornation about website we given.

          telnet example.com 80

It gather open information about website of example.com with ipaddress and code of website present.

<img width="1580" height="615" alt="Nessus scanners-output-img" src="https://github.com/CharanCSE02/Task-4-Firewall-testing/blob/main/Screenshot 2025-09-28 195708.png" />

# SSH
The ssh is used operating remotly for other ip address(or) system.It means we conneted with your system by ssh.

SSH means Secure Shell Serivce with port 22.To start ssh we need work command.

        sudo systemctl start ssh

        sudo systemctl status ssh

To connect remotly we need know ip address of system.To connection we need run command in remote system.

        ssh username@ipadrs

<img width="1580" height="615" alt="Nessus scanners-output-img" src="https://github.com/CharanCSE02/Task-4-Firewall-testing/blob/main/Screenshot 2025-09-28 220834.png" />

# Rules adding process
Rules is only process to control the traffic.

<img width="1580" height="615" alt="Nessus scanners-output-img" src="https://github.com/CharanCSE02/Task-4-Firewall-testing/blob/main/Screenshot 2025-09-28 221601.png" />


# Rules to block telnet 
To block the telnet we need port number 23.Next click of add rules name is telnet then select deny(or)reject with in/out traffic is deny.

In above figure 1 already rule is present.


# Rule to allow ssh
To allow the ssh we need port number 22.Next click of add rules anme is ssh then select allow with in/out traffic is allow.
