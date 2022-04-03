# Project 9 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: __________________

Description:

<img src="blue-vuln1.gif">


## Green

Vulnerability #1: Cross-Site Scripting

Description: Go to /public/contact.php. File the form with script injection. The input will be inline html in /public/staff/feedback/index.php. This creates vulnerability of executing malicious code.

<img src="https://github.com/Codepath-Twitter-Clone/CyberSecurity_Unit9/blob/main/g1.gif">

## Red

Vulnerability #1: __________________

Description:

<img src="red-vuln1.gif">

