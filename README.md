# security.txt

## Frequently Asked Questions

### What is the main purpose of security.txt?
The main purpose of security.txt is to help make things easier for companies and security researchers when trying to secure platforms. Thanks to security.txt, security researchers can easily get in touch with companies about security issues.

### Is security.txt an RFC?
security.txt is currently an Internet draft that has been submitted for RFC review. This means that security.txt is still in the early stages of development. We welcome contributions from the public: https://github.com/securitytxt/security-txt

### Where should I put the security.txt file?
For websites, the security.txt file should be placed under the /.well-known/ path (/.well-known/security.txt) [RFC8615]. It can also be placed in the root directory (/security.txt) of a website, especially if the /.well-known/ directory cannot be used for technical reasons, or simply as a fallback. The file can be placed in both locations of a website at the same time.

### Are there any settings I should apply to the file?
The security.txt file should have an Internet Media Type of text/plain and must be served over HTTPS.

### Will adding an email address expose me to spam bots?
The email value is an optional field. If you are worried about spam, you can set a URI as the value and link to your security policy.


## References
 * https://securitytxt.org
 * https://www.rfc-editor.org/rfc/rfc9116
