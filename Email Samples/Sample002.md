

Subject: YOUR $2.500,000.00

This email pretends to be from Jeff Bezos, impersonating the founder of Amazon.com. The goal is to trick recipients into believing they’ve won a massive cash prize. It’s a plain-text phishing lure, and the sender uses a free Gmail account, clearly not affiliated with Amazon. The absence of Amazon branding and the generic tone show this is a low-effort mass phishing attempt.
 

1. Header Analysis

From: edmondasiimwe0@gmail.com
A free Gmail address not connected to Amazon or Jeff Bezos in any way. This is an immediate red flag.

Display Name:
MR. JEFFREY BEZOS
Using a well-known name to appear credible. This is basic impersonation, as no business would send millions using this display method.
 




Return-Path: edmondasiimwe0@gmail.com
Same as the sender, This confirms this came from a personal Gmail account, not an organization.

Reply-To: mrjeffreyprestonbezos07@gmail.com
Another Gmail address, even more suspicious. Phishers often use a Reply-To address to direct replies away from detection.
 

Originating IP:  209.85.208.169
This is a Google mail server (rDNS: mail-lj1-f169.google.com). Nothing suspicious on its own, but irrelevant since Gmail allows abuse by phishers using free accounts.
rDNS:
mail-lj1-f169.google.com
This matches Google — further confirming this was sent using Gmail’s infrastructure.
  

Email Security:

 
•	SPF:  Pass
SPF (Sender Policy Framework) checks if the sending IP is allowed to send for the domain, it  has valid a SPF records since it uses gmail’s infrastructure, although that doesnt make it safe.

•	DKIM:  Neutral
Gmail attempted DKIM verification, but it returned neutral, meaning it couldn’t fully verify the sender's identity.

•	DMARC: Pass
Gmail’s DMARC policy is configured properly — but this does not confirm this is safe, since anyone can use Gmail to impersonate others.



2. Content of the Email

Subject:
YOUR $2.500,000.00

Message Body:

Dear E-mail Owner,

My name is Jeff Bezos, an American, investor, and charity donor. I'm
the founder, CEO and president of Amazon.com. Your email address
has won you ($2,500,000.00). Kindly get back to me so I know your email
address is valid. (mrjeffreyprestonbezos07@gmail.com)

Regards,
Mr Jeffrey Preston Bezos

 Red Flags in Message Content:
•	Generic greeting: “Dear E-mail Owner”, it clearly lacks personalization.
•	Unbelievable claim: Winning millions from Jeff Bezos without entering any contest.
•	Suspicious contact address: Another Gmail account is used to “confirm” your win.
•	No formal structure: No Amazon branding, footer, or even proper formatting.
•	Emotional bait: Uses the "free money" angle to excite and lower your guard.









3. Attachment / Link
 
•	Attachment: None
•	URL in Message: http://amazon.com
o	Domain: amazon.com (legitimate, but possibly used to trick you into trusting the message)
o	Path: /
o	Scheme: HTTP (no HTTPS — insecure usage)
o	Port: 80
o	VirusTotal: 0/94 — No detection, but that’s irrelevant here as this link seems included to lend false credibility rather than being the real phishing endpoint.

This technique is called brand laundering — using a known domain to build trust, while interaction is redirected to a Gmail address.

4. Behaviour and Visuals
 
•	Plain-text message, no Amazon logos, no headers and no styling.
•	Impersonation of Jeff Bezos using fake Gmail addresses.
•	Tries to build trust using Jeff Bezos’s name and Amazon mention.
•	Low effort — typical of mass-sent email scams.
•	Visuals: None. No branding, no images, no signatures — just plain text.
•	Tone: Informal and opportunistic.

5. Final Report
This is a basic mass phishing scam, relying on greed and name recognition. It uses impersonation, false claims of winnings, and personal Gmail addresses to trick victims into initiating contact.

Red Flags Summary:
•	Free Gmail sender and reply-to addresses
•	Pretends to be Jeff Bezos with no verification or branding
•	Poorly written, no personalization
•	No SPF/DKIM/DMARC from any real Amazon domaing
•	Includes amazon.com as a false trust signal
•	Message promises millions — a classic fraud tactic
•	Plain text, no visual authenticity
