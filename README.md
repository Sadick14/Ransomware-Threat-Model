# Ransomware-Threat-Model
A threat model to protect ECG from ransomware attacks

Get the PDF:
[Ransomware Threat Model for Electricity Company of Ghana (ECG).pdf](https://github.com/Sadick14/Ransomware-Threat-Model/files/15190693/Ransomware.Threat.Model.for.Electricity.Company.of.Ghana.ECG.pdf)

# ARTICLE 
For about five days now some customers of the largest electricity seller in the country, Electricity Company of Ghana (ECG) have been unable to buy power and others have had their power off for days without respite, because some sections of the company’s systems have been hacked, ghanabusinessnews.com has been told by people familiar with the crisis.

According to these sources who have asked not to be named because they say it is a sensitive matter bothering on potential national security, some sections of the ECG project site situated near the Kwame Nkrumah Circle in Accra has been infiltrated by ransomware, and the hacker or hackers have changed the source code and taken control of parts of the server.

An ethical hacker who also didn’t want to be named said a ransomware is a type of virus that hackers who have access to a server would introduce and create a C2C or command and control centre.

“They then establish control of your server at their end and encrypt all your data with public and private keys and then initiate negotiations for money,” the ethical hacker said.

The ethical hacker also said to assure their victims that they have hacked into their servers, hackers would ask the victim to send them some of the encrypted files to decrypt as proof.

Another source says, the hackers have encrypted sections of the ECG system crippling it from functioning. “The hacker or hackers have encrypted the system and the system is now demanding that a code is entered to decrypt it,” the source said.

It is not known yet how the hacker or hackers got access to the ECG servers.

The ECG reportedly works with about 14 independent service providers, but these providers do not have access to the ECG servers remotely, unless they go on site or ECG itself creates a virtual private network (VPN) for them to be able to work off site.

While ECG officials haven’t spoken specifically on the extent of cyber attack, the puzzle being resolved now is to figure out how the hacker or hackers gained access to the ECG servers, because according to the ethical hacker, it’s the first step to introducing the ransomware into the server.

“There are however ways to take back control, if ECG has backups. But from the way the crisis has gone on for this long I get the impression that either ECG has backups on the same server or they don’t have backups at all,” the ethical hacker said.

Another anonymous source said another way ECG can resolve the issues is to restart its system, in which case it would lose all it’s files and logs, and then re-register all the customers on the system.

“They however need the logs to trace the issue and to find the hackers, so that is not an option,” the source said.

Other sources have said there are ransomware experts in Ghana who will be able to resolve the issues if they are able to locate the payload which the hackers might have put on the ECG system and do reverse engineering if the payload is one of those sold and bought online and are not strong like custom made ransomware.

The ECG has been designated a critical infrastructure by law because of its significance to lives. Critical infrastructure around the globe have become targets for ransomware attacks in recent times.

Mr Charles Nii Ayiku Ayiku, General Manager in charge of external communications at the ECG told Ghana Business News that while he doesn’t have any information of hacking or attack on the systems, said they have technical challenges, adding that the ECG has stabilised its district offices and they are able to sell power to consumers. The systems for third-party vendors however, he says are still unstable.

He also stated that the ECG has extended its working hours to ensure that all customers who have been affected by the situation can buy power.

Meanwhile, National Security and Cybersecurity officials have been working with the company to find resolution to the crisis.

By Emmanuel K. Dogbevi

Copyright ©2022 by NewsBridge Africa
All rights reserved. This article or any portion thereof may not be reproduced or used in any manner whatsoever without the express written permission of the publisher except for the use of brief quotations in reviews.

This article provides a detailed account of a ransomware attack on the Electricity Company of Ghana (ECG), which has resulted in significant disruptions to its operations. Let's break down some key points and potential areas for further analysis or exploration in your project work:

    Nature of the Attack: The article describes how sections of ECG's systems have been infiltrated by ransomware, leading to encryption of data and loss of control over parts of the server. This highlights the destructive capabilities of ransomware and its potential impact on critical infrastructure.

    Impact on Operations: Customers have been unable to buy power, and some have experienced prolonged power outages due to the attack. This underscores the real-world consequences of cyber attacks on essential services and the importance of cybersecurity measures for organizations like ECG.

    Challenges in Resolution: The article mentions difficulties in resolving the attack, including the uncertainty surrounding how the hackers gained access to ECG's servers and the potential absence of backups. These challenges could serve as focal points for discussing the importance of cybersecurity preparedness, incident response strategies, and backup policies in mitigating the impact of ransomware attacks.

    Response and Collaboration: ECG officials, cybersecurity experts, and government agencies are mentioned as being involved in addressing the crisis. This highlights the collaborative effort required to respond effectively to cyber threats and the role of coordination between public and private sectors in cybersecurity governance.

    Legal and Regulatory Considerations: The designation of ECG as critical infrastructure and the involvement of national security and cybersecurity officials suggest the broader legal and regulatory implications of cyber attacks on essential services. Exploring relevant laws, regulations, and frameworks pertaining to cybersecurity and critical infrastructure protection could provide additional context for your project.

    Technical Analysis: The article briefly touches on technical aspects of ransomware, such as encryption techniques and potential methods for restoring control over the affected systems. Delving deeper into the technical details of ransomware attacks, including common attack vectors, encryption algorithms, and countermeasures, could enhance the technical depth of your project.

    Ethical and Privacy Concerns: Considerations regarding data privacy, confidentiality, and ethical considerations in handling ransomware incidents may also warrant discussion. This could involve examining ethical dilemmas faced by organizations in responding to ransom demands and protecting sensitive information during and after a cyber at

  # Threat Model
  Based on the information provided in the article, here's a threat model tailored to the ransomware attack scenario on the Electricity Company of Ghana (ECG):

    Threat Actor: The primary threat actor in this scenario is the unknown hacker or group of hackers who perpetrated the ransomware attack on ECG's systems. The motivations behind the attack could include financial gain, disruption of services, or even geopolitical motives.

    Attack Vector: The attack vector used by the threat actor to infiltrate ECG's systems and deploy ransomware is not explicitly mentioned in the article. However, potential attack vectors could include phishing emails, exploiting unpatched vulnerabilities in software or systems, or gaining unauthorized access through weak or compromised credentials.

    Vulnerabilities:
        Lack of robust cybersecurity measures, including inadequate network segmentation, weak access controls, and insufficient monitoring and detection capabilities, may have contributed to the success of the attack.
        Absence of regular data backups or inadequate backup procedures may have exacerbated the impact of the ransomware by limiting the organization's ability to restore encrypted data.
        Potential misconfiguration or unpatched software vulnerabilities in ECG's systems could have provided the attacker with initial access to the network.

    Assets at Risk:
        Critical infrastructure components, such as power generation, distribution, and billing systems, are the primary assets at risk in this scenario.
        Customer data, including personal information and billing records, may also be at risk of exposure or compromise due to the ransomware attack.

    Likelihood and Impact:
        Likelihood: The likelihood of ransomware attacks targeting critical infrastructure organizations like ECG is increasing globally, given the potential for financial gain and disruptive effects on essential services.
        Impact: The impact of the ransomware attack on ECG is significant, resulting in disruptions to power supply, financial losses, reputational damage, and potential legal and regulatory repercussions.

    Mitigation Strategies:
        Implement robust cybersecurity controls, including network segmentation, access controls, intrusion detection systems, and regular security audits and assessments.
        Maintain up-to-date software patches and security updates to mitigate known vulnerabilities and reduce the attack surface.
        Establish and regularly test comprehensive data backup and recovery procedures to ensure the organization's ability to restore critical systems and data in the event of a ransomware attack.
        Provide cybersecurity awareness training for employees to recognize and mitigate common attack vectors, such as phishing emails and social engineering tactics.
        Collaborate with government agencies, industry partners, and cybersecurity experts to share threat intelligence, best practices, and incident response capabilities.
