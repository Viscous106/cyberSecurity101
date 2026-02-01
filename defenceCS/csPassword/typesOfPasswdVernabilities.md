# 🛡️ Commercial Cyber Security Notes: Securing Accounts 🛡️

## Reference Video:
- [How to Secure Your Online Accounts](https://www.youtube.com/watch?v=fJYdAN4Vh5c)

## Notes:

### 1: Understanding and Preventing Dictionary Attacks

A **dictionary attack** attempts to guess passwords by trying a pre-compiled list of common words, phrases, or previously compromised passwords. Attackers use automated tools to rapidly test these potential credentials against a target account.

#### Prevention Strategies:
1.  **Strong, Unique Passwords**: Use long (12-16+ characters), complex passwords combining letters, numbers, and symbols. Never reuse passwords.
2.  **Multi-Factor Authentication (MFA)**: Adds an extra layer of security, making it harder for attackers even with a compromised password.
3.  **Account Lockout Policies**: Temporarily lock accounts after multiple failed login attempts to slow down attacks.
4.  **Rate Limiting & CAPTCHA**: Limit login attempts per IP and use CAPTCHA to deter bots.
5.  **Education & Password Managers**: Educate users on password best practices and encourage the use of password managers.

### 2: Understanding and Preventing Brute-Force Attacks

A **brute-force attack** systematically tries every possible combination of characters until the correct password is found. Unlike dictionary attacks that use pre-defined lists, brute-force attacks generate and test all possible character combinations, making them more exhaustive but also more time-consuming.

#### How it works:
1.  **Systematic Guessing**: Automated tools attempt every possible character combination (e.g., "a", "b", "c", ..., "aa", "ab", ...).
2.  **Increased Complexity, Increased Time**: The time required increases exponentially with password length and complexity.

#### Prevention Strategies:
Prevention strategies for brute-force attacks are largely similar to those for dictionary attacks, as both rely on automated password guessing:
1.  **Strong, Unique Passwords**: The primary defense. Longer and more complex passwords significantly increase the time and computational resources required for a successful brute-force attack.
2.  **Multi-Factor Authentication (MFA)**: Essential for adding a second verification step, rendering a guessed password insufficient.
3.  **Account Lockout Policies**: Crucial for blocking attackers after a few failed attempts.
4.  **Rate Limiting**: Restricts the number of login attempts per time unit, making brute-force attacks impractical.
5.  **CAPTCHA/reCAPTCHA**: Helps distinguish between human users and bots.
6.  **Network-Level Protections**: Firewalls and intrusion detection/prevention systems (IDS/IPS) can detect and block suspicious login activity.
7.  **Monitor Login Attempts**: Regularly review logs for unusual patterns of failed login attempts.

By implementing these comprehensive measures, the risk of both dictionary and brute-force attacks can be significantly mitigated.

---

## Rules for Staying Safe from Password Vulnerabilities:

1.  **Create Strong & Unique Passwords for Every Account**:
    *   **Length is Key**: Make your passwords at least 16 characters long.
    *   **Complexity Matters**: Mix uppercase and lowercase letters, numbers, and symbols.
    *   **No Personal Info**: Avoid using your name, birthday, or other easily guessable information.
    *   **One Account, One Password**: Never reuse passwords across different services. If one account is breached, all your accounts are at risk.

2.  **Enable Multi-Factor Authentication (MFA) Everywhere**:
    *   MFA is your best defense, even if your password is stolen. It requires a second form of verification (like a code from your phone) to log in.
    *   Prioritize enabling MFA on critical accounts like email, banking, and social media.

3.  **Use a Password Manager**:
    *   It's nearly impossible to remember dozens of strong, unique passwords. A password manager can generate and securely store them for you.
    *   You only need to remember one strong master password for the manager itself.

4.  **Beware of Phishing Scams**:
    *   Be skeptical of unsolicited emails, texts, or calls asking for your login information.
    *   Always verify the sender and go directly to the official website instead of clicking on suspicious links.

5.  **Keep Your Software and Devices Updated**:
    *   Software updates often contain critical security patches that protect you from the latest threats.
    *   Enable automatic updates on your operating system, web browser, and other applications.

6.  **Regularly Review Your Account Activity**:
    *   Periodically check your login history and connected applications on important accounts.
    *   If you see any suspicious activity, change your password immediately and revoke access for any unrecognized devices or apps.

7.  **Avoid Using Public Wi-Fi for Sensitive Tasks**:
    *   Public Wi-Fi networks are often unsecured, making it easier for attackers to intercept your data.
    *   If you must use public Wi-Fi, use a Virtual Private Network (VPN) to encrypt your connection.
