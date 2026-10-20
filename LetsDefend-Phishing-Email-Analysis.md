# Lab 002 — Phishing Email Analysis

**Platform:** LetsDefend  
**Challenge:** Phishing Email  
**Badge Earned:** Phishing Analyzer  
**Completion Date:** October 20, 2026  
**Category:** Security Operations Center (SOC) / Email Security  
**Status:** Completed

## Objective

Investigate a suspicious email claiming to originate from PayPal and determine whether it displays indicators of phishing.

## Scenario

A user received an unexpected email written in German that appeared to originate from PayPal. The email was provided for examination in a controlled LetsDefend lab environment.

## Investigation Process

1. Accessed the phishing email challenge in LetsDefend.
2. Examined the email and its header information.
3. Identified the Return-Path field and learned its role in email delivery.
4. Examined the URL contained in the email and identified its domain.
5. Located the Received-SPF header to investigate the sending server's IP address.
6. Evaluated the available evidence to determine whether the email was suspicious.
7. Submitted the challenge responses and successfully completed the exercise.

## Tools and Concepts

- LetsDefend virtual lab environment
- Email header analysis
- Return-Path
- Sender Policy Framework (SPF)
- IP address identification
- URL and domain analysis
- Phishing detection

## Skills Developed

- Navigating and examining email headers
- Distinguishing email addresses, domains, and IP addresses
- Recognizing potential phishing indicators
- Conducting a structured email security investigation

## Lessons Learned

This exercise helped me understand how email metadata can support a phishing investigation. I practiced locating technical evidence rather than relying solely on the email's visible appearance.

I also learned that identifying the sending server and examining linked domains are useful steps when determining whether an email is legitimate.

## Outcome

Successfully completed the LetsDefend Phishing Email challenge and earned the **Phishing Analyzer** badge.

