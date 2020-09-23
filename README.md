# Elk-Project_Part_2

Completed the following tasks:
•	Implement the alarms and thresholds you determined would be effective in Project 2.
•	Assess two more vulnerable VMs and verify that the rules work as expected.
•	Use Wireshark to analyze live malicious traffic on the wire.

Lab Environment
•	Capstone (192.168.1.105): The vulnerable target VM that you will attack to test alerts. Filebeat and Metricbeat are installed and will forward logs to the ELK machine.
o	Please note that this VM is in the network solely for the purpose of testing alerts.
•	ELK (192.168.1.100): The same ELK setup that you created in Project 1. It holds the Kibana dashboards.
•	Kali (192.168.1.90): A standard Kali Linux machine for use in the penetration test on Day 1.
o	Credentials are root:toor.
•	Target 1 (192.168.1.110): Exposes a vulnerable WordPress server.

Day 1: Use WPScan to access a WordPress target. Configure alerts in Kibana and test them by attacking Target 1 repeatedly.
Day 2: Use Wireshark to capture and analyze traffic on a virtual network.
Day 3: Work in groups to create presentions of the analysis.
