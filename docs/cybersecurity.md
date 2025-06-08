---
title: "Cybersecurity"
author: by cptsubtxt
date: "2025-06-07"
subject: "Cybersecurity, Web Application, Networking"
subtitle: "Hitchiker's Guide for becoming a web security researcher"
keywords: [Cybersecurity, Threads, Tools, Burp Suite, ZAP, OWASP]
book: true
lang: "en"
titlepage: true
toc-own-page: true
classoption: [oneside]
...

# Introduction

## Your Cybersecurity Journey starts here

Welcome and thank you for coming with us on that journey. So buckle up and we are going to check out the fundamental Concepts that build the Cybersecurity space.

Afterwards we will learn about the different kinds of attacks. During the journey we always try to do some quizzes and test out differnt attacks.

We also try to sort out different technics to make our knowlegde usable in a structured way to explore systems.

So happy learning and nice adventures!

## A brief history of cybersecurity

Here is a footnote reference,[^1]

[^1]: Here is the footnote.

## How to learn cybersecurity

## How to setup a training environment

# I. Foundations of Cybersecurity & Networking

When starting in the field of cyber security it is crucual to understand the foundations of core cyber security concepts.

## A. Core Cybersecurity Concepts

## B. Networking Fundamentals

### OSI Model & TCP/IP Model

Understanding how networks function at different layers.

### Common Network Protocols

Deep dive into HTTP/HTTPS, DNS, TCP, IP, FTP, SSH, etc.

### Network Topologies & Devices

Routers, switches, firewalls, load balancers.

### IP Addressing & Subnetting

Basic understanding of network segmentation.

### Proxies & VPNs: How they work and their relevance in security.

# II. Web Application Fundamentals & Architecture

# III. Web Security Vulnerabilities & Attack Vectors

## A. OWASP Top 10 (2021 Edition)

With [https://owasp.org/www-project-top-ten/](OWASP Top 10 (2021))

### A01:2021 - Broken Access Control

Horizontal Privilege Escalation
Vertical Privilege Escalation

### A02:2021 - Cryptographic Failures

          Weak encryption
          improper key management
          sensitive data exposure

### A03:2021 - Injection

          SQL Injection: Classic
          Error-based
          Blind (Boolean-based, Time-based)
          Second-order
          Out-of-band
          Command Injection
            OS Command Injection
          NoSQL Injection
          LDAP Injection
          XXE (XML External Entity) Injection
          Server-Side Template Injection (SSTI)

### A04:2021 - Insecure Design

          Threat modeling
          secure design patterns

### A05:2021 - Security Misconfiguration

          Default credentials
          Unnecessary services
          Misconfigured headers

### A06:2021 - Vulnerable and Outdated Components

          Identifying and patching known vulnerabilities in libraries and frameworks

### A07:2021 - Identification and Authentication Failures

          Brute-force
          Weak credentials
          session management issues

### A08:2021 - Software and Data Integrity Failures

          Insecure deserialization
          Insecure CI/CD pipelines

### A09:2021 - Security Logging and Monitoring Failures

          Lack of logging
          Ineffective monitoring

### A10:2021 - Server-Side Request Forgery (SSRF)

          Basic SSRF
          Bypassing filters

## B. Other Common Web Vulnerabilities

### Cross-Site Scripting (XSS)

Reflected
Stored
DOM-based

### Cross-Site Request Forgery (CSRF)

### Insecure Direct Object References (IDOR)

### File Upload Vulnerabilities

Malicious file uploads

### HTTP Request Smuggling

### Web Cache Poisoning

### Deserialization Vulnerabilities

### Business Logic Flaws

Exploiting application logic flaws
race conditions

### Rate Limiting Bypass

### CORS Misconfigurations

### Clickjacking (UI Redressing)

### WebSocket Security Vulnerabilities

## C. Attack Surface Mapping & Reconnaissance

### Information Gathering: Passive vs. Active reconnaissance

With this Attack vectors information should be disclosed that reveal sensitive information to Website Users e.g.:

- Data about other users, such as usernames or financial information
- Sensitive commercial or business data
- Technical details about the website and its infrastructure

Examples include:

- Revealing the names of hidden directories, their structure, and their contents via a robots.txt file or directory listing
- Providing access to source code files via temporary backups
- Explicitly mentioning database table or column names in error messages
- Unnecessarily exposing highly sensitive information, such as credit card details
- Hard-coding API keys, IP addresses, database credentials, and so on in the source code
- Hinting at the existence or absence of resources, usernames, and so on via subtle differences in application behavior

### Subdomain Enumeration

### Directory/File Enumeration

### Port Scanning

### Fingerprinting Technologies

### OSINT (Open Source Intelligence) for web applications

## D. Exploitation Techniques

Manual Exploitation: Understanding the mechanics of attacks.
Automated Tools: Using scanners and exploit frameworks (e.g., Metasploit for relevant modules).

# VI. Tools of the Trade for Web Security Research

# V. Web Application Penetration Testing Methodology

# VI. Secure Coding Principles & Best Practices

# VII. Advanced Topics & Specializations (Path to Bug Bounty Hunting)
