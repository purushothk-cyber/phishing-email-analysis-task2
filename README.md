# Phishing Email Analysis – Task 2

## Objective
This task aims to identify and analyze the characteristics of phishing in a suspicious email that pretends to be from Microsoft 365 Support. The purpose is to develop email threat detection skills and raise awareness about common phishing tactics.

## Sample Phishing Email Overview

- **Email Display Name**: Microsoft 365 Support
- **Sender Address**: support@office-365-notifications[.]com
- **Recipient**: john[.]doe@mybusiness[.]com
- **Subject**: Security Alert – Recover Your Account
- **Screenshot Filename**: `phishing_microsoft_email.png`

##  Identified Phishing Indicators

### 1. Suspicious Sender Email
- Domain is not official. Microsoft would never use `@office-365-notifications.com`.
- Official domains include `@microsoft.com`, `@accountprotection.microsoft.com`, etc.

### 2. Urgent & Fear-Based Language
- The email creates panic by claiming unauthorized access:
  > "Someone else has accessed your account..."
  > "Act now or your account will be locked."

### 3. Suspicious Button
- The **“Recover Account”** button is a trap likely leading to a phishing site.
The link destination is unknown and cannot be verified from the image, but this tactic is common in phishing.

### 4. Generic Greeting
- Email is addressed to an email ID, not a specific name.
- Legitimate companies usually personalize emails.

### 5. Branding Deception
- Uses Microsoft layout, fonts, and colors to **trick** users — this is called **brand impersonation**.

## Summary & Conclusion

This is a **classic phishing email** that attempts to:
- Steal credentials using urgency
- Trick users with spoofed email and branding
- Redirect victims to malicious links

### Recommendations
- **Do not click** on links/buttons.
- **Report** the email to the security team or Microsoft.
- **Delete** the message immediately.

## Tools & Methods Used
- Manual inspection of email content
- Hover analysis (link destination, not shown)
- Visual phishing traits check
