# WebHacking

This a collection of my portfolio tools and helfup tips. Before you begin drink thee and relax your mindsuite


XXS

SQLI

SSRF

CRLF

CSV

LFI

XXE

RCE

Open Redirect

Template injection

# The Web Application Hacker's Handbook
Web Application Hacker's Handbook Task checklist as a Github-Flavored Markdown file
## Contents
- [Recon and analysis](#recon-and-analysis)
- [Test handling of access](#test-handling-of-access)
- [Test handling of input](#test-handling-of-input)
- [Test application logic](#test-application-logic)
- [Assess application hosting](#assess-application-hosting)
- [Miscellaneous tests](#miscellaneous-tests)

## Task Checklist

### Recon and analysis

- [ ] Map visible content
- [ ] Discover hidden & default content
- [ ] Test for debug parameters
- [ ] Identify data entry points
- [ ] Identify the technologies used
- [ ] Map the attack surface

### Test handling of access
- [ ] Authentication
- [ ] Test password quality rules
- [ ] Test for username enumeration
- [ ] Test resilience to password guessing
- [ ] Test any account recovery function
- [ ] Test any "remember me" function
- [ ] Test any impersonation function
- [ ] Test username uniqueness
- [ ] Check for unsafe distribution of credentials
- [ ] Test for fail-open conditions
- [ ] Test any multi-stage mechanisms
- [ ] Session handling
- [ ] Test tokens for meaning
- [ ] Test tokens for predictability
- [ ] Check for insecure transmission of tokens
- [ ] Check for disclosure of tokens in logs
- [ ] Check mapping of tokens to sessions
- [ ] Check session termination
- [ ] Check for session fixation
- [ ] Check for cross-site request forgery
- [ ] Check cookie scope
- [ ] Access controls
- [ ] Understand the access control requirements
- [ ] Test effectiveness of controls, using multiple accounts if possible
- [ ] Test for insecure access control methods (request parameters, Referer header, etc)

### Test handling of input

- [ ] Fuzz all request parameters
- [ ] Test for SQL injection
- [ ] Identify all reflected data
- [ ] Test for reflected XSS
- [ ] Test for HTTP header injection
- [ ] Test for arbitrary redirection
- [ ] Test for stored attacks
- [ ] Test for OS command injection
- [ ] Test for path traversal
- [ ] Test for script injection
- [ ] Test for file inclusion
- [ ] Test for SMTP injection
- [ ] Test for native software flaws (buffer overflow, integer bugs, format strings)
- [ ] Test for SOAP injection
- [ ] Test for LDAP injection
- [ ] Test for XPath injection

### Test application logic

- [ ] Identify the logic attack surface
- [ ] Test transmission of data via the client
- [ ] Test for reliance on client-side input validation
- [ ] Test any thick-client components (Java, ActiveX, Flash)
- [ ] Test multi-stage processes for logic flaws
- [ ] Test handling of incomplete input
- [ ] Test trust boundaries
- [ ] Test transaction logic

### Assess application hosting

- [ ] Test segregation in shared infrastructures
- [ ] Test segregation between ASP-hosted applications
- [ ] Test for web server vulnerabilities
- [ ] Default credentials
- [ ] Default content
- [ ] Dangerous HTTP methods
- [ ] Proxy functionality
- [ ] Virtual hosting mis-configuration
- [ ] Bugs in web server software

### Miscellaneous tests

- [ ] Check for DOM-based attacks
- [ ] Check for frame injection
- [ ] Check for local privacy vulnerabilities
- [ ] Persistent cookies
- [ ] Caching
- [ ] Sensitive data in URL parameters
- [ ] Forms with autocomplete enabled
- [ ] Follow up any information leakage
- [ ] Check for weak SSL ciphers

## References
*  http://mdsec.net/wahh/tasks.html
