# Incident-Report
Google Cybersecurity Specialization Portfolio - Use the NIST-CSF to respond to a security incident
<p>The National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF) is a voluntary
framework that outlines standards, guidelines and best practices for businesses of all sizes to manage
cybersecurity risk. It has 5 domains under which each organization has to follow. They are:
<ol>
  <li>Identify</li>
  <li>Protect</li>
  <li>Detect</li>
  <li>Respond</li>
  <li>Recover</li>
</ol>
<strong>Synopsis</strong></br>
To understand how to apply the NIST CSF, I was given this security incident synopsis (scenario) below:
Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Network monitoring software to detect abnormal traffic patterns

An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.</br></br>
<b>Summary</b></br>
The Organization experienced a DDoS attack which stopped it’s internal network. The cybersecurity team investigated and found that a threat actor sent a flood of ICMP pings to the company’s network via an unconfigured firewall. The team was able to block the incoming ICMP packets and restore all critical network service.</br></br>
<b>Identify</b></br>
The potential gap is in the unconfigured firewall which allowed the malicious actor to overwhelm the entire organization’s internal network through a flood of ICMP packets. The network needs to be restored.</br></br>
<b>Protect</b></br>
The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out some of the ICMP traffic based on the suspicious behaviour.</br></br>
<b>Detect</b></br>
To improve the monitoring capabilities and to increase the speed and efficiency of detection, the cybersecurity team sourced for the IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. Likewise, a network monitoring software was implemented to detect abnormal traffic patterns.</br></br>
<b>Respond</b></br>
For future security events, the cybersecurity team will isolate the affected systems to prevent further disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. The team will analyze the network logs to check for suspicious and abnormal activity and report any incidents to the upper management.</br></br>
<b>Recover</b></br>
The network services will be restored to a normal state by the team. The ICMP flooding will be blocked at the firewall level (using iptables – for Linux Operating Systems). All non-critical network services should be stopped to reduce internal network service. Critical network services should be restored first, then, once the flood of ICMP packets have timed out, all non-critical network systems and services can be brought back online.</br></br>
</p>
