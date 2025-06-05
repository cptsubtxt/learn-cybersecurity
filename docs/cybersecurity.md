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
classoption: [oneside]
...

# Introduction

The following text is meant to be your Guide to the cybersecurity learning path.

In the first section we are covering the foundations of cybersecurity topics to get a broad understanding of

Aftewards the second section will be going deeper into the domain of Webapplications and their various variants.

Happy Learning!

# I. Foundations of Cybersecurity & Networking

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

With (https://owasp.org/www-project-top-ten/)[OWASP Top 10 (2021)]

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

## D. Exploitation Techniques

# VI. Tools of the Trade for Web Security Research

# V. Web Application Penetration Testing Methodology

# VI. Secure Coding Principles & Best Practices

# VII. Advanced Topics & Specializations (Path to Bug Bounty Hunting)
