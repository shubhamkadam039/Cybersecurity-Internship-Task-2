# Cybersecurity-Internship-Task-2
# Phishing Email Analysis

## Overview
Analyzed a sample phishing email impersonating Microsoft Office365 triggering a "high-severity alert".

## Phishing Indicators Found

1. **Sender Address Spoofing**
   - The actual sending domain ("email-records.com") is not Microsoft's authentic address. Phishing often uses deceptive domains to look legitimate.

2. **Urgency and Fear Tactics**
   - The subject line and message convey urgency (“high-severity alert has been triggered”) to prompt users to act rashly without proper scrutiny.

3. **Suspicious Links**
   - Prominent CTA (“View alert details”) likely points to a malicious external site. Always hover over buttons/links to check their real destination.

4. **Generic Recipient Info**
   - The recipient field shows “sent by Unknown” and does not personalize the recipient, which is typical of mass phishing.

5. **Grammar and Formatting Issues**
   - Minor issues, such as awkward spacing and inconsistent formatting, may indicate the email isn't professionally crafted by Microsoft.

6. **Impersonation of a Trusted Brand**
   - Use of Office 365 and Microsoft branding attempts to gain user trust. Always verify sender authenticity with official channels.

## How I Analyzed
- Reviewed sender address and headers.
- Hovered over all links.
- Checked for urgency/fear tactics.
- Looked for grammar and formatting mistakes.
- Used VirusTotal & MXToolbox to analyze links/headers.

### Conclusion
This sample demonstrates multiple classic phishing traits:
- Spoofed sender domain.
- Urgent, fear-inducing language.
- Suspicious call-to-action links.
- Impersonation of trusted brands.
- Lack of personalization and minor grammar errors.
- It is a type of 'Tech Support Phishing Scam'.

## Screenshots
Attached with this repository

