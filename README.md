# Codepath Week 9

# Honeypot Deployed

I deployed the Dionaea honeypot using MHN. 

# Issues Encountered

I had to spend some extra time learning how to use the Google Cloud Platform and setting up my account. During Milestone 1, it was taking  a very long time to complete the firewall. I had to restart the process and enable the API for my project. During Milestone 4, I could not access the External IP for MHN admin. To resolve this, I had to allow HTTP and HTTPS traffic for the VM.  

# Data

The application was deployed on April 14th, 2018. After about an hour, there were 78 attempted attacks. After four hours, there were 437 attacks. After 24 hours, there were 1402 attacks. The attacks primarily came from the United States and Russia. The top attacker came from China. Most attacks used the pcap protocol. 

Top 5 Attacker IPs:
1. 123.249.9.72 (92 attacks)
2. 77.72.82.72 (90 attacks)
3. 5.188.11.37 (84 attacks)
4. 174.138.92.116 (56 attacks)
5. 5.188.9.25 (41 attacks)
 
Top 5 Attacked ports:
1. 23 (135 times)
2. 3306 (118 times)
3. 80 (75 times)
4. 5060 (67 times)
5. 445 (62 times)


# Questions

I am curious if the IPs listed are all authentic or if some of them may be spoofed. In some rare cases, the country of origin could not be identified. 
