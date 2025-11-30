## Disclaimer
All SQL injection examples, exploitation steps, and vulnerability demonstrations contained in this repository were 
performed exclusively in controlled, simulated lab environments created for educational and cybersecurity training purposes.

No testing was performed on live systems, third-party applications, or any environment without explicit authorization.
This content is intended solely to demonstrate secure coding practices, common vulnerabilities, and ethical penetration testing methodology.

# SQL Injection Allowing for Login Bypass
**Severity:** 
**Component / Endpoint:**
**Tested:**

### 1 - Summary
A SQL Injection vulnerability flaw in the login form allows attackers to bypass authentication easily. This flaw arose due to unsanatized user
input being directly concatenated into the SQL query. Thus, forcing the query to grant access without the proper credentials.

## 2 - Environment
-
