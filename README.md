# Phishing-Email-Analysis
This project is focused on analyzing phishing emails and classifying them as either:  Malicious or  Non-malicious 

Email Analysis 

The Problem : 

Phishing remains one of the most successful attack methods in cybersecurity. It's cheap for attackers, easy to launch, and sadly, still effective.

Below is an history of phishing attacks from recent times

1. Sony Pictures (2014) : A phishing email led to one of the biggest entertainment leaks ever. Sensitive employee data, unreleased films, and private messages were exposed, costing the company millions and public trust.

2. Ubiquiti Networks (2015) : An employee was tricked into transferring $46.7 million to attackers via a simple business email compromise (BEC) phishing scheme.

3. Google & Facebook (2013–2015) : A Lithuanian scammer posed as a hardware vendor and tricked both tech giants into wiring $100 million+ to fake accounts ,just with legit-looking emails.

These are not made-up stories. These are real-world, high-impact damages caused by phishing. 


Project Goal

The goal of this project is focused on analyzing phishing emails and classifying them as either:

Malicious (Phishing)
or
Non-malicious (Safe)

The scope is to dig into real email samples, dissect them from the inside out, and understand what makes it malicious or non-malicious, so we can detect and stop them better.



Tools Used

To keep it practical , I used a combination of online tools and manual analysis:

PhishTool –  For in-depth email structure and metadata analysis.

VirusTotal – To scan URLs and attachments for known malware or phishing behavior.

Google Translate – When dealing with foreign-language phishing attempts.

MXToolbox – For checking domain health and blacklists.



Email Analysis Structure

To evaluate each email, I broke it down using these four standard techniques:

1. Header Analysis
There is a lot of information in  email headers ,  Below are some of the information: found in email headers: 

From , To , Date , Subject , Return-Path , Received , Message-ID , Reply-To , Content-Type , SPF (Sender Policy Framework) , DKIM (DomainKeys Identified Mail) and the DMARC (Domain-based Message Authentication, Reporting & Conformance) 
I focused on only a few of them  for this project


2. Content Analysis
This involves checking the body of the message for:
•	suspicious claims 
•	Urgent language and emotional bait
•	Suspicious links, incorrect formatting, and poor grammar 


3. Attachment Analysis
This deals with inspection of any attached files to check:
•	File type and name
•	Obfuscation techniques
•	Upload results from VirusTotal 


 4. Behavioral Analysis
 Not all phishing is obvious — some rely on user behavior. So we consider:
•	What action it wants the user to take (click, reply, download)
•	Whether that behavior is logical or risky


Final Report

Each email is documented thoroughly in a structured format with a detailed breakdown.
I explain why it’s phishing or not, and highlight all the red flags.
This goes beyond jut detection ,it’s about understanding the psychology, design, and technique behind phishing emails.

 

The Importance of this Project and a call to action

Too many organizations ignore email threats until it’s too late. But phishing is still the #1 entry point for cyberattacks, especially ransomware.
Below are ways in which companies can nullify this threats 

•	Enable SPF, DKIM, and DMARC to prevent spoofed emails from reaching employees.
•	Train staff continuously — phishing is a human-targeted threat.
•	Use email filters and threat detection systems that catch common indicators of phishing.
•	Encourage reporting — make it easy for users to report suspicious emails, not shameful.

If companies actually implement these simple but powerful steps, they can prevent most phishing-based attacks before any damage is done. That’s why this project isn’t just about building technical skills, it’s also about building solutions that help real businesses protect their data and people.


