# 🧠 Behavioral Health Resource Navigator

![Status](https://img.shields.io/badge/status-In%20Development-blue)
![AI](https://img.shields.io/badge/AI-Claude-orange)
![Public%20Health](https://img.shields.io/badge/Public%20Health-Behavioral%20Health-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

> **An AI-powered decision-support tool that helps Behavioral Health Bureau staff quickly locate trusted community resources and generate consistent referral summaries.**

🚧 **Status:** In Development  
🎯 **Focus:** AI for Public Health | Behavioral Health | Decision Support  
👩🏾‍💻 **Author:** Rachel Acheampong

---

## Overview

The Behavioral Health Resource Navigator is designed to help Behavioral Health Bureau staff quickly find relevant community resources using natural language instead of manually searching through PDFs, websites, and resource guides.

By reducing search time and standardizing referral information, staff can spend more time supporting clients and less time navigating documentation.

---

## The Problem

Behavioral health professionals often spend valuable time searching through lengthy PDFs, websites, and resource guides to find the right services for clients.

This process can be slow, inconsistent, and especially difficult for staff who are less comfortable navigating multiple documents while assisting someone in real time.

---

## The Solution

The Behavioral Health Resource Navigator uses AI to make finding resources as simple as asking a question in plain English.

Instead of manually searching through documents, staff can ask questions like:

> "Find outpatient mental health services for adults that don't require insurance."

The assistant retrieves relevant resources and presents them in a clear, structured format.

---

## Intended Users

- Linkage to Care
- Education & Training
- Criminal Justice, Policy & Crisis Response

---

## Current Features

- AI-powered natural language search
- Resource lookup
- Insurance-free resource filtering
- Referral summary generation
- Easy-to-use interface for non-technical staff

---

## Planned Features

- Resource comparison
- Spanish language support
- Analytics dashboard
- Search history
- Feedback collection
- Automatic resource updates

---

## Example Questions

- Find free outpatient mental health services for adults.
- What substance use treatment programs do not require insurance?
- Compare Program A and Program B.
- Generate a referral summary for this client.
- Find behavioral health services near downtown St. Louis.

---

## System Architecture

```mermaid
flowchart TD
    A[Behavioral Health Staff] --> B[Ask a Question]
    B --> C[AI Resource Navigator]
    C --> D[Behavioral Health Resource Guide]
    D --> C
    C --> E[Relevant Resources]
    C --> F[Referral Summary]
