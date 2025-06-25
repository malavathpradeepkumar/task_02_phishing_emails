# task_02_phishing_emails

Email Analysis Report

I received an email from captchas.io with the subject "hCAPTCHA Solving Back and Stable." The email claims their hCaptcha solving service is back online and working 
fast and stable. The message encourages users to upgrade or subscribe to their service.

Technical Details:

The email was received on June 21, 2025, at 01:27 AM (PDT).

The sender address was noreply@captchas.io.

The email passed SPF and DMARC authentication checks, which means it came from an authorized server for the domain captchas.io.

The sending server IP was 190.2.130.169, and it matched the domain’s allowed list.

The email headers showed it was sent via SMTP with TLS encryption, ensuring the email was securely transmitted.

The message is an HTML email with embedded styles and a logo image linked from captchas.io.

Operating System and Commands:

The headers mention Exim mail server version 4.98.2 running on a server with a hostname ln-svr-01.captchas.io.

The email was received and processed on a Linux system, which can be confirmed by the presence of commands like cat used to view the raw email content and headers during analysis.

cat command is often used to display the contents of files, in this case, it helps to examine the full email source.

Suspicious Observations:

Although the email passed authentication and looks professional, automated captcha solving services like this can sometimes be linked to bot activities or abuse, so it’s important to be cautious.

The message urges users to upgrade or subscribe quickly, which might be a marketing tactic but can also pressure users to act without full verification.

The service claims to work on most websites but admits it might not work on some, which is vague and could be misleading.

The email domain and IP appear legitimate, but I did not test the actual links or services to verify safety.

Since the email is promoting a service that might be used to bypass security captchas, it may have ethical or legal implications.

Summary:

The email looks like a legitimate transactional email from captchas.io, verified by technical checks. The content is straightforward but promotes a service that might be sensitive or controversial. Using commands like cat on a Linux system helped me inspect the full email headers and content to confirm its source and authenticity.

For the project, I saved screenshots of the email content and headers and also copied the raw email source using command line tools for deeper analysis.

