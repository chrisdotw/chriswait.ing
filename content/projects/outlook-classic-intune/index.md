---
title: "Outlook Classic Deployment via Intune"
date: 2025-04-07
summary: "Deploying Outlook Classic as an available Company Portal app for users who required the desktop client."
tags:
  - Microsoft 365
  - Intune
  - Application Deployment
  - Windows
tech_stack:
  - Microsoft Intune
  - Microsoft 365 Apps
  - Company Portal
  - Windows 11
featured: true
status: "Completed"
role: "Implementation and Testing"
duration: "Completed rollout"
highlights:
  - "Microsoft 365 Apps deployment configured for Outlook only"
  - "Available install through Company Portal"
  - "Validated working installation approach"
---

A targeted application deployment project to provide Outlook Classic on managed Windows devices without unnecessarily installing additional Microsoft 365 desktop applications.

## Requirement

Some users required Outlook Classic on managed devices while maintaining a simple, user-friendly installation process.

## Solution

Configured **Microsoft 365 Apps for Enterprise** through Intune with Outlook selected as the required application component, then assigned it as an available application through Company Portal.

## Outcome

The approach provided a reliable self-service installation experience and gave users access to the required Outlook desktop client using an Intune-managed method.

## Lessons Learned

Where a supported first-party Intune deployment option meets the requirement, it is preferable to overcomplicating packaging or scripting.
