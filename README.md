# PT-webapp-methodology
Authentication:
Can we enumerate user accounts?
- Registration page
- Login page
- Password reset page

Is there any brute-force protection?
- Check for account lockouts
- Check for rate limiting
- Check for CAPTCHA
- Check for MFA

What is the password policy?
- Check the strength requirements
- Is the password stored securely? (E.g. if we reset, will it send us the cleartext password)
- Is the password reset token sufficiently unique?

Are credentials predictable?
- Check for default credentials
- Check for username conventions (E.g. firstname.lastname)

Is autocomplete enabled on password fields?

Check the password reset functionality
- Knowledge-based questions
- Token leakage via Referrer
- Token predictability

Is authentication happening client-side?

Are there any backups or leaked files with creds?

Is there remember me or auto login functionality?
- Are the tokens for this predictable?
- How long does the token remain valid?

Are tokens or credentials passed via the URL?

Are there CSRF tokens?
