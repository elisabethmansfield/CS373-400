#### Elisabeth Mansfield
#### mansfiee@oregonstate.edu
#### 7-Jul-2019
#### CS373
#### Week 2 Write-Up

## My Thoughts, Impressions, and Conclusions about the Material:

Most of this material is very new to me. Therefore, my first impressions are primarily gut reactions to the instructor, tools, concepts, and overall material. This professor/instructor (Christiaan Beek) is clearly brilliant. He is an experienced professional in the field who knows a lot about the inner workings of the industry. Since I am a working professional, I hold a lot of respect for individuals who are experts in their area of expertise. While watching these videos, I feel like I need to hang on every single word he says, because his advice is very insightful and relevant to the industry. Even his off-hand or mumbled comments are chock-full of good tips and advice. Therefore, I tend to proceed very slowly through the lecture videos, listening closely to everything he says and taking very detailed notes. This is a challenge since there are many videos to proceed through (12 videos this week, over 3 hours of footage). It is also challenging because he speaks with an accent that I am unfamiliar with. However, if I pause the video frequently, use the captions feature, and proceed at my own pace, I can slowly grow to understand the meaning behind his words. In other words, he really knows what he is talking about, and I really want to understand every single thing that he is trying to communicate to me.

## Description of the Basic Concepts:

-	**Incident Response (IR)**: The IR team is responsible for reacting quickly to a security incident. An “incident” is some form of security breach (e.g. a hack). During this event, the IR team must gather volatile and non-volatile data without modifying it. They must also create an event timeline and log all of their actions, down to the minute, in order to create an understandable evidence trail.

-	**Forensic Analysis**: This is the process of identifying, preserving, and analyzing digital evidence to be potentially used in a civil or criminal case. A good forensic analyst should be able to easily replicate and understand what happened on the system. Forensic Analysis includes live forensics, post-mortem forensics, network-based forensics, and more.

-	**APT**: An APT is an Advanced Persistent Threat (such as malware) that poses a continuous threat to a system(s). These types of threats require a different type of forensic process/procedure. Often, the APT is not alerted to the system until the “Installation” or “Command and Control” steps, however, the alert may arrive as early as the “Delivery” step (e.g. in a Spam folder).

-	**DMZ**: This term is from military terminology that means “demilitarized zone”. It is a safety zone in between the “outside world” (e.g. the entire internet) and the “inside world” (e.g. our corporate network). This is the in-between, where you place the honeypots and other internet-connected devices that are protected by firewalls.

-	**Order of Volatility**: The order by which you should gather the forensic evidence. While collecting evidence, you should proceed from the most volatile to the least volatile. If a particular piece of evidence is prone to easily disappear (e.g. RAM memory), it should be gathered first.

-	**FTK Imager**: A free and open-source tool used to gather volatile and non-volatile forensic evidence. This tool uses a user-friendly GUI on Windows OS. It is used to acquire memory dumps from a suspect’s machine.

-	**Volatility**: A tool used on the Windows command line to gather forensic evidence. Volatility is compatible with numerous plugins (including Yara). Many of the compatible plugins are useful for malware detection and analysis.

-	**Yara**: Yara is one of many plugins for the Volatility tool. It is also one of the many “malware-specific” plugins that are available for Volatility. 

## Figures and Code Samples:

My attempts to launch Volatility from the VMWare Remote Console were unsucessful, as I was met with the below error message. I had to capture this screengrab quickly before the console window quickly exited.

![logo](https://github.com/elisabethmansfield/CS373-400/blob/master/Week2/images/logo.jpg?raw=true) 

## New Ideas and Tools Learned and Conclusions Reached:

Everything I learned this week is completely new to me, including many of the Windows tools. I usually work in an OSX or Linux environment, so the Windows command line and system tools are still very new to me. Additionally, it is my first time working with Volatility, FTK Imager, PhotoRec, and pretty much every tool discussed this week. 

All of them make sense as low-level intelligence tools for forensic analysis. Forensic analysis is all about gathering as much corroborative data as possible to build a fact-based case about the event(s) that occurred. For example, Triage is the process of proving that a piece of evidence is correct by replicating its result by different means. Therefore, the forensic analyst must use multiple tools to gather the most accurate system data as possible. 
