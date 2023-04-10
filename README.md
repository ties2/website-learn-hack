

***Web Application attacks***

* [SQL Injection](https://github.com/ties2/web-pentest/wiki/Sql-injection-Attack)
* [XSS](https://github.com/ties2/web-pentest/wiki/XSS-Attack)
* [CSRF](https://github.com/ties2/web-pentest/wiki/CSRF-Attack)
* [ClickJacking](https://github.com/ties2/web-pentest/wiki/ClickJacking-Attack)
* [Dom-Based](https://github.com/ties2/web-pentest/wiki/Dom-Based-Attack)
* [CORS](https://github.com/ties2/web-pentest/wiki/CORS-Attack)
* [XXE](https://github.com/ties2/web-pentest/wiki/XXE-Attack)
* [SSRF](https://github.com/ties2/web-pentest/wiki/SSRF-Attack)
* [Request Smuggling](https://github.com/ties2/web-pentest/wiki/Request-Smuggling-Attack)
* [Command Injection](https://github.com/ties2/web-pentest/wiki/Command-Injection-Attack)
* [Server-side template injection](https://github.com/ties2/web-pentest/wiki/Server-side-template-injection-Attack)
* [Insecure deserialization](https://github.com/ties2/web-pentest/wiki/Insecure-deserialization-Attack)
* [Directory Traversal](https://github.com/ties2/web-pentest/wiki/Directory-Traversal-Attack)
* [Access Control](https://github.com/ties2/web-pentest/wiki/Access-Control-Attack)
* [Authentication](https://github.com/ties2/web-pentest/wiki/Authentication-Attack)
* [OAuth Authentication](https://github.com/ties2/web-pentest/wiki/OAuth-Authentication-Attack)
* [Business logic vulnerabilities](https://github.com/ties2/web-pentest/wiki/Business-logic-vulnerabilities-Attack)
* [web cache poisoning](https://github.com/ties2/web-pentest/wiki/web-cache-poisoning-attack)
* [HTTP host header attacks](https://github.com/ties2/web-pentest/wiki/HTTP-host-header-attacks-attack)
* [WebSockets](https://github.com/ties2/web-pentest/wiki/WebSockets-attack)
* [Inforamtion Disclosure](https://github.com/ties2/web-pentest/wiki/Inforamtion-Disclosure-attack)
* [File upload vulnerabilities](https://github.com/ties2/web-pentest/wiki/File-upload-vulnerabilities-Attack)
* [JWT attacks](https://github.com/ties2/web-pentest/wiki/JWT-attacks-attack)
* [Prototype Pollution](https://github.com/ties2/web-pentest/wiki/Prototype-Pollution-Vulnerability)


***

**some solutions for each of the web application security vulnerabilities:**

SQL Injection:
Use prepared statements with parameterized queries or use an ORM to sanitize input and prevent malicious SQL statements from being executed.
***
XSS (Cross-Site Scripting):
Use input validation and sanitization to prevent malicious scripts from being injected into web pages. Also, use Content Security Policy (CSP) to restrict the sources of scripts and enforce safe inline scripts.
***
CSRF (Cross-Site Request Forgery): 
Use anti-CSRF tokens to validate requests and ensure that they originated from a legitimate user.
***
ClickJacking: 
Use X-Frame-Options header to prevent web pages from being embedded in an iframe and restrict clickjacking attacks.
***
DOM-Based: Use client-side input validation and sanitization to prevent DOM manipulation attacks.
***
CORS (Cross-Origin Resource Sharing): Use proper CORS headers to restrict access to resources from other domains.
***
XXE (XML External Entity): Disable external entity parsing or use input validation to prevent malicious XML entities from being processed.
***
SSRF (Server-Side Request Forgery): Use input validation and whitelisting to restrict the URLs that can be accessed by the server.
***
Request Smuggling: Use HTTP/2 or HTTPS to prevent request smuggling attacks.
***
Command Injection: Use input validation and sanitization to prevent malicious commands from being executed on the server.
***
Server-side Template Injection: Use template engines that restrict access to server-side variables and enforce safe variable substitution.
***
Insecure Deserialization: Use input validation and sanitize serialized data to prevent malicious objects from being deserialized.
***
Directory Traversal: Use input validation and restrict access to sensitive directories to prevent directory traversal attacks.
***
Access Control: Use proper access control mechanisms to restrict access to sensitive resources.
***
Authentication: Use strong authentication mechanisms such as multi-factor authentication to prevent unauthorized access.
***
OAuth Authentication: Use OAuth 2.0 with proper access token management to ensure secure authentication.
***
Business Logic Vulnerabilities: Use threat modeling to identify potential business logic vulnerabilities and use input validation and sanitization to prevent them.
***
Web Cache Poisoning: Use proper caching mechanisms that restrict the content that can be cached to prevent cache poisoning attacks.
***
HTTP Host Header Attacks: Use a whitelist of valid hostnames to prevent host header attacks.
***
WebSockets: Use secure WebSocket connections with proper origin validation and restrict access to sensitive resources.
***
Information Disclosure: Use proper error handling mechanisms to prevent sensitive information from being disclosed.
***
File Upload Vulnerabilities: Use input validation and restrict access to uploaded files to prevent file upload vulnerabilities.
***
JWT Attacks: Use proper JWT validation mechanisms and restrict the sources of JWT tokens to prevent JWT attacks.
***
Essentials Skills: Keep up-to-date with web application security trends, attend security conferences, and get certified in web application security.
***
Prototype Pollution: Use input validation and sanitization to prevent prototype pollution attacks, use libraries that have built-in protection against prototype pollution.Wiki Prototype Pollution is a type of security vulnerability that affects applications that use JavaScript Object Notation (JSON) objects. It occurs when an attacker can manipulate or inject properties and methods into an object's prototype chain, leading to unexpected or malicious behavior in the application.







