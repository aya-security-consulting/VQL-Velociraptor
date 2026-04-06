# Contributing

Thank you for your interest in contributing to **VQL-Velociraptor**.

This repository aims to provide high-quality **Velociraptor Query Language (VQL)** content for **threat hunting, DFIR, incident response, and forensic investigations**.

## How to Contribute

You can contribute by:

- Adding new VQL queries
- Improving existing queries
- Fixing formatting or logic issues
- Optimizing query performance
- Adding documentation or use cases
- Suggesting new hunting categories

## Contribution Principles

Please make sure contributions are:

- Relevant to defensive security, DFIR, or threat hunting
- Technically accurate
- Tested where possible
- Clearly named and categorized
- Easy to read and maintain
- Safe to review before production use

## Query Submission Guidelines

When submitting a new VQL query, please:

1. Place it in the most relevant folder
2. Use a clear filename
3. Add a short description at the top of the file
4. Keep formatting clean and consistent
5. Avoid unnecessary complexity
6. Mention important assumptions or limitations

## Recommended Query Header

Please use a simple header like this in each query file:

```sql
/*
Name: Suspicious_Scheduled_Tasks
Category: Persistence
Description: Hunt for scheduled tasks executing LOLBins or suspicious arguments.
Author: Your Name
*/
