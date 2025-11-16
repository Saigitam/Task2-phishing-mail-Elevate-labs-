# Task2-phishing-mail-Elevate-labs-
Analyze a phishing mail sample
# 
#  🛡️ Cyber Security Internship – Task 2: Phishing Email Analysis

### Internship Program: Elevate Labs Cyber Security Internship 
### Task Objective: Analyze a suspicious email to identify phishing indicators.
#### Name: Kothamasu Sai Prasad

## 1. ✉️ Email Sample Used for Analysis

The following suspicious email was analyzed:

From: authenticationmail@trust.ameribank7.com   
To: johnsmith@email.com     
Subject:  A new login to your bank account

Bank of America 
   
Dear account holder,   
There has been a recent login to your bank account from a new divice:   
IP address: 192.168.0.1  
Location: Miami, Florida   
4 new transactions have been made with this account since your last login.

If this was not you, please reset your password immediately with this link:
https://trust.ameribank7.com/reset-password

Thank you,                            
Bank America]

(https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Example_bank_phishing_email.svg/1200px-Example_bank_phishing_email.svg.png)


This email claims to be from Bank of America but contains multiple inconsistencies, suspicious elements, and social engineering tactics.

## 2. 🔍 Phishing Indicators Identified (With Explanations)
### 2.1 Spoofed / Fake Sender Address


• Sender uses authenticationmail@trust.ameribank7.com  
• Legitimate Bank of America emails come from @bankofamerica.com  
• Domain contains misleading keywords and numbers (trust, ameribank7)

#### ➡ Indicator: Fake or spoofed domain.

### 2.2 Incorrect Bank Name

• Email signs off as “Bank America”  
• Official name is Bank of America  

##### ➡ Indicator: Impersonation with incorrect branding.

### 2.3 Suspicious / Malicious Link

• The link points to:
https://trust.ameribank7.com/reset-password   
This domain is not related to Bank of America.

##### ➡ Indicator: Possible phishing website designed to steal credentials.

### 2.4 Fake Technical Information

• IP address shown: 192.168.0.1  
• This is a private/local IP, not a public IP used for login alerts.

##### ➡ Indicator: Attackers used fake technical data to appear legitimate.

### 2.5 Urgent Social Engineering Tone

• Email pressures the user to reset password immediately  
• Mentions suspicious login, transactions, and a new device

##### ➡ Indicator: Classic social engineering technique to cause panic.

### 2.6 Grammar & Spelling Errors

Examples in the email:

• “divice” instead of device     
• “Bank America” instead of Bank of America

##### ➡ Indicator: Poorly written phishing message.

### 2.7 Generic Greeting

• Uses “Dear account holder” instead of the actual name.

##### ➡ Indicator: Phishers often send mass emails and lack user-specific info.

## 3. ⚠️ Summary of Phishing Traits


|  **Category**                | **Suspicious Findings**        |
|-----------------------------|--------------------------------|
| Fake domain                 | ameribank7.com                 |
| Incorrect branding          | Signed as “Bank America”       |
| Malicious link              | Fake reset-password link       |
| Urgency tactic              | “Immediately reset”            |
| Technical misinformation    | Private IP used                |
| Spelling errors             | “divice”                       |
| Generic greeting            | “Dear account holder”          |


## 4. 🔒 Security Risk Assessment

The email is a high-risk phishing attempt that could result in serious security breaches, including:

• Credential theft (stealing login details)  
• Malware installation (by tricking the user into visiting malicious sites)  
• Bank account compromise  
• Identity theft  
• Unauthorized financial transactions

The attacker uses urgency and fear-based social engineering to pressure the user into clicking a fraudulent password-reset link and revealing sensitive information.

## 5. 🛡️ Recommended Mitigation Measures

To safeguard against similar phishing attempts:

• Do not click on unexpected password-reset links.  
• Always verify sender domains before opening links.  
• Hover over links to inspect actual URLs.  
• Report suspicious emails to the security team or email provider.  
• Enable multi-factor authentication (MFA) to reduce risk from stolen passwords.  
• Keep security awareness updated to recognize social engineering attempts.
