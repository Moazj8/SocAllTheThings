## Diving into Threat Hunting
What and Why TH ?
TH is a security process that hunts for malicious or suspicious activities that may have previously evaded detection, and it enables security analysts to diving Deep to find malicious actors, Identify malicious actor that have evaded SOC detection, Stop actor dweal time in network, enhancing detection policys and leveraging various technologies, tools, and methodologies to identify and respond to security threats. And TH can be both Proactive and Reactive, proactive when you have- team, plans, structure and reactive after incident- by gathering the insights from incident.

Types of TH?
• Hypothesis-driven investigation : Often triggered by a new threat that identified in wild and Hunter will assume the actor is already in network and start investigation and Identify the TTP and convert them into queries to discover if they found in the network.
• IOC driven investigation: Involves input from tactical Threat Intelligence to capture known IOC and IOA and perform retro hunt to increase the dataset and gather more IOC, also convert them into queries to discover if they found in the network.
• Analytics and ML driven investigation: Parsing large amout of dataset using ML driven algorithm and Find outliner within the logs Pivot from outliners and start investigation

Now we have good understanding of TH, let's jump into the Hunting process.

Hunting Process:
1- Create a Hunting loop and plan for the Hunt Cycle.
2- Create a Hunting Report documenting your hunt objective, what you are hunting for, where you are hunting. If you have multiple  hypothesis for a single hunt, mention them like H1, H2, H3 etc. You can break one hypothesis into multiple parts as well, like H1A, H1B etc.
3- What type of Hunting are you planning to perofm, if it's a custom one based on custmer requirments or they're proactively executed based on situations you can mention the same.
4- Finally Resources/Tools you may use.


Conclusion :
TH is important and can provides visibility into your network, confidence in your security posture, helps organizations identify threat actors, their likely targets and which types of attacks they're likely to use.
