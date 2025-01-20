# Web Application Security 

## About Web Application Security:
# Chapter 1:
## Introduction 
 Web application security is an important aspect of cyber security that focuses on the protection of web applications from potential threats.
 #### - Key concepts of web application security are:
 Authentication, Authorisation, Data encryption, Input Validation, Session Management, Error Handling.
 #### - Importance of Web Application Security are:
 Data protection, Reputation Management, Compliance, Financial Security.

 # Chapter 2:
 
## Testing methodologies on Web Applications:
To ensure Cyber Security of Web Application different types of testing methodologies are used.
These methodologies helps in  detecting  vulnerability , Strengthen security control and protect web applications for multiple threats.

#### - Some of the testing methodologies are as follows:
#### • Vulnerability Assessment - It identifies the known vulnerabilities of  Web Applications with the help of some tools like: Nessus, Open VAS, Nikto.
#### • Penetration Testing - It exploits vulnerabilities by stimulating real-world attacks with the help of OWASP ZAP, Burp Suite, etc.
#### • Static Application Security Testing (SAST)- It identifies security vulnerabilities using source code with the help of Fortify, Checkmark etc.
#### • Dynamic Application Security Testing (DAST)- It detects run time vulnerabilities by testing running application by using IBM AppScan , OWASP ZAP, etc.
#### • Fuzz Testing - It tests application by unexpected or random data using tools like Peach Fuzzer, AFL, etc 
#### • Security Configuration Testing - It checks the defaults like misconfiguration , credentials and open ports and validate the Encryption and security policies.
#### • Dependency and Component Analysis - It detects vulnerabilities by scanning dependencies by using OWASP dependency check, black duck, etc.
#### • API Security testing - It identifies the vulnerabilities of APIs and then stimulate API injection and replay attacks.
#### • Business logic testing - It identifies vulnerabilities of application workflows that can be misused.
# Chapter 3:
## DevSecOps:
DevSecOps is an approach that combines Development (dev), Security (sec) and Operations (ops) all together so that, security can be integrated in the life cycle of software development. It's main focus is to develop or deploy security to be automated or continuous at every stage instead of adding it in last.
#### It's objective is to deliver secure software rapidly and effectively.It also automate manual security processes to increase it's accuracy and efficiency.
#### Various types of tools used in DevSecOps are Version Control Tools (like Git, GitHub, GitLab), CI/CD tools (like Jenkins, Axure DevOps), Security tools (like Burp Suit, OWASP ZAP, Snyk, SonarQube), Monetring tools (like Splunk, Datadog, Prometheus).
#### Benifits of DecSecOps are  Early Threat Detection, Faster Dilevery, Improved Security Postures and Regulatory Compliance.


# Chapter 4:
## What are different SAST and DAST Tools:
SAST(Static Application Security Testing) and DAST(Dynamic Application Security Testing) in cyber security plays an important role. These tools are used to detect vulnerabilities in different applications. Let us see some of their examples-
#### - SAST Tools (Static Application Testing Tools):
These tools analyse the code without make them run in its development phase and detect the vulnerabilities in it.
#### 1- SonarQube - It is an open source tool that detects the code quality and vulnerabilities.

#### 2- Checkmarx - It is an enterprise- grade SAST tool that support multi language.

#### 3- Fortift Static Code Analyzer(SCA) - Comprehensive static code analysis tool by Micro Focus.

#### 4- Veracode - It is a cloud based platform that provide SAST and remediation suggestion.

#### 5- CodeQl - It is a  GitHub tool that detects vulnerabilities through query language.

#### - DAST Tools (Dynamic Application Testing Tools):
These tools test an application in run-time and stimulate real- world attack.
#### 1- OWASP ZAP (Zed Attack Proxy) - It is free or an open source tool that detects web app vulnerabilities.

#### 2- Burp Suite - It is a popular penetration testing tool that provides manual and automated DAST features.

#### 3- Netsparker - It is an web app vulnerability scanner that detect SQL injection and XSS.

#### 4- Acunetix - It is an automated tool that detect vulnerabilities in web apps and APIs.

#### 5- AppScan - It is an IBM tool that offers comprehensive dynamic testing features.

## Difference between SAST and DAST tools :
The basic difference between SAST and DAST tools are their time and testing approaches. Some more differences are -

#### Testing Approach - 
##### - DAST - It test application in its runtime.
##### It stimulates live attacks on web applications and APIs.
##### It identifies vulnerabilities with developer's prospective.

##### - SAST - It analyze code without get it executed.
##### It analysis source code, binaries, byte code.
##### It searches for vulnerabilities with developer's prospective.

#### Testing phase -
##### - DAST - It is used in testing and production phase.
##### It detect vulnerabilities after the deploy of application 
##### - SAST - It uses in early development phase.
##### It detects vulnerabilities in coding stage.

#### Types of vulnerabilities detected -
##### - DAST - Run-time issues like : Authentication flaws , Misconfigurations , OWASP Top 10 Vulnerabilities.
##### - SAST - Code- level issues like : SQL Injection , Buffer Overflow, Cross-Site Scripting (XSS).

#### Speed and Integration - 
##### - DAST - It is a time consuming process as it stimulates live attacks.
##### It is suitable for run-time testing.
##### - SAST - It is a fast or less time taking process but it has a lot false positives 
##### It can be easily integrated in CI/CD pipelines.


# Chapter 5:

## Securing Web page efficiently:
Securing Web Applications efficiently is an important aspect as insecure page is considered as a soft target to hackers. 
We can improve security of our web pages using some of the best practices of cyber security using some steps such as - 
##### - By Implementing HTTPS (Securing communication):
Enable HTTPS by installing SSL and TLS certificate , it encrypts our data , it secures from man-in-the-middle attack and it also avoid browser warnings.
##### - By using strong password and authentication:
Impliment strong password policies for login forms and use multi- factor authentication that reduses the risk of unauthorised access.
##### - Input validation and Sanitization:
Validate user inputs and encode HTML special character to avoid Cross-Site Scripting. It prevent attacks like SQL Injection and XSS.
##### - Use security headers:
Block Malicious Script and use Strict-Transport- Security. It reduces browser based attacks.
##### - Keep software updated:
Keep web servers, CMS and plugins updated and impliment security patches quickly that prevents exploitation of known vulnerabilities.
##### - Limit user permissions and Access:
Impliment role-based access control and limit file system permissions. It avoids unauthorised changes and data breaches.
##### - Regular Security Testing:
Use automated tools like OWASP ZAP and Burp Suite , Prefer vulnerability accessement and penetration testing that helps in detecting real-world vulnerabilities and also helps in fixing them.
##### - Backup Regularly:
Schedule automated backups and encrypt backups  and store them securely through which quick recovery of data is possible after a cyber attack and memory loss.



