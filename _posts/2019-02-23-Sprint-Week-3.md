---
layout: "post"
title: Sprint Week 3
 
---
Reflection 

This week I had to concentrate on completing the presentation on tools based on password crackers and actually attempting to complete attacking and breaking into system as this was a requirement for the subject and/or joining a program for breaking into machines. This mostly accenturated by attempting the Help HTB (Hack the Box), popcorn and legacy HTB attempts. Other importance learning Invoked this week included learning how to capture the flag on Deloitte, SecTalks and PwnLabs.Init (went through the walkthrough as the machine still couldn't work) were other activities that I completed during this week. With industry guidence, one of the guys presenting on Wednesday gave assistance such as mentioning SSL and to use metasploit console. I also started using OWASP zap and understanding how the tool functions to generate reports for the user that finds vulnerabilities. 

SecTalks is another factor in my learning as the involvement in understanding various tools used to intercept analogy signals and converting it to pcaps was interesting to comprehend. listening to industry is another major incident in where I got some experience in the field and to engage with real security professionals and how read teaming and blue teamings functions, the areas that the cyber field offers as metioned on their sides and their experiences which includes Web Application Penetration Testing, Mobile Application Testing and Code Review, Physical Security and Social Engineering and Red Team Operations. Another personal insight that was gained through this week was through Jai's presentation of the challenge, mentioning that we shouldn't have done what the presenters had done as they had knowledge of the port. In a real World scenario in which we wouldn't have access to the port, there are different nmap commands that we could use in this situation.

Attempting the help htb challenge.

This week's use of netdiscover was to discover machines through my virtual machine. I had to downloaded virtual box as VMware couldn't detect the machines that I was trying to break into, furthermore, as there were attempts of other challanges this took me hours to configure at which I decided it was best to do HTB challenges. I tryed consistently changing from a bridged to a NAT configuration, checking the MAC address and seeing if it alined with the one of pwnLab.Init and the other various machines that were linked on Microsoft Teams. Using nmap and understanding how nmap functions was another major incident in where I came to understand how nosiy the tool is and the way I should use it properly. Searching the apache website and the version of the apache showed that there were flaws so it was useful to understand what the commands could do such as -sC would generate a safe script and -oA would create a file that outputs the search. Using wget to get content from the webservers and to download the HTTP, this helpped me by I guess going through the fo;es tjat were downloaded. Using dirb (directory buster) tool and its various commands to find directories that I couldn't access helpped find a website 10.10.10.121/support, which had a ticket page that allows the user to submit tickets, with this I was thinking of doing XSS exploits but couldn't find the time to do so and other SQL injections that I could exploit. While hacking through the websites and the use of burp suite to intercept the site 10.10.10.121, an apache webstie through a poxy and editing the headers to figure out what I could do to the website. When interpeting 10.10.10.121/support, I found that there was a cookie with a PHPSESSIONID that I could exploit.

Free For All 
In the free-for-all, there were a lot that was learnt through communicating and interacting with other fellow studio student. Through their explanation of how they approached this week's task involved with hacking into a system. This learning activity involved understanding how other students deal with their situations and how they solve problems by finding viable solutions. Futhermore, the technical detail shared with each other helps all of us to understand certain conceots such as learning how someone had a reverse shell in their challenges, Corey's HTB (I think from hearing it) and Cameron finding an exploit through HTTP.

Monday

Jason

Jason was messing with webservers images via XVWA (extremely vulnerable web app) through vuln-hub and was messing wih the web image. He also did his reflection during the weekends.

David 

David did various web challenges on monday and discovered there was a way to get XSRF on burp Suite

Friday

Cameron

Cameron explain through his approach to complete this week's task was to hack into a machine known as kioptrix level 1 through WTF exploit, this is by going through searchsploit and by finding a vulnerability in mod_SSL.

Corey

Corey attempted to complete legacy and Bake on HTB and had vproblems with the directory travesal.  

Harry 

Harry did HTB walkthrough popcorn and Raven 2 walkthrough.

Feedback that I recieved

The constructive feedback that was reciveved encouraged from the representative during the industry presentation accentuated a more better understanding of how to engage with challenge. THe recent speech given to the studio to my understanding wasn't satisfactory to complete the SLO as I believed that there needs to be clarity in my speaking, more eye contact and be more engaging to the audience. Another aspects I believe I failed in was completing an active hack the box challenge as it had become difficult and I had wasted more time than needed on configuring my machines rather than actually doing the challenges. I also need to further understand more commands and how they function, adopting a pen tester's mindset is also anther important aspect that I need to work on. This involves how I would approach the problem, how would I approach it. 


The feedback that I recieved will be further evaluated onto my portfolio, need to improve public speaking issues and my presentation issues to achieve the SLO outcomes hopefully by next week. Time management is still a reocurring issue as I need to be more effective evaluate where to use my time effectively and not waste most of the time attempt to get the machines to work. Hence, currently understanding the content this week dispite it being heavy and will still continue attempting more challenges in the future. 

References / Artefacts

Presentation on Wednesday 

https://docs.google.com/presentation/d/1LgbOMyO1fvXfUz_TwheiM4_RSzKEuBLUawDL1DWPNVA/edit#slide=id.g50438cf9b5_3_10

Security Password Tools Research

https://docs.google.com/document/d/1YFz8iwUdMEjCkpiFXQVxc4CMtRabEaehq3DdKgADF_U/edit#

Images on HTB attempt

https://docs.google.com/document/d/1memy3_qVn0HtVL6m_kQEy4HBSEQE-i-8xldktHpERUo/edit

Images of Notes on Free-For-ALL

https://docs.google.com/document/d/15PuXJGT0-pd1DEshAeN80tKanJ0_azTqukJsJXvYvA4/edit

