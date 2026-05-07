# Project 360 Casino Training — Privacy Policy and Data Deletion

Last updated: 2026-05-05

## Contents

- [Overview](#overview)
- [What we collect](#what-we-collect)
- [How we use it](#how-we-use-it)
- [Authentication providers](#authentication-providers)
- [How we share data](#how-we-share-data)
- [Encryption](#encryption)
- [Data retention](#data-retention)
- [Data deletion request](#data-deletion-request)
- [Your rights](#your-rights)
- [Changes to this policy](#changes-to-this-policy)
- [Contact](#contact)

## Overview

Project 360 Casino Training ("the app") is an internal training platform for casino staff. The app is invite-only: accounts are created by administrators on behalf of individual users. This policy explains what data the app collects, why, how it is protected, and how a user can request deletion of their account and associated data.

## What we collect

The app collects the following categories of data:

- **Account identifiers**: user ID and device identifier.
- **Profile information**: name and email address, obtained from your authentication provider (Google or Apple) when you sign in.
- **App activity**: training module progress, video watch progress, exercise responses, completion records.
- **Diagnostic data**: in-app error logs and crash information.
- **Security event logs**: authentication attempts, permission denials, device changes, rate-limit events. These logs include an IP address and a coarse country and city derived from that IP for fraud-detection purposes. This information is collected server-side, not from device location services. The app does not request or use device location permissions.

The app does **not** collect: precise or approximate location from device sensors, contacts, calendar, photos beyond those a user voluntarily uploads, microphone audio, camera images, financial information, health information, web browsing history, or messages from other apps.

## How we use it

Collected data is used solely to:

- Authenticate users and authorize access to training content.
- Track individual progress and provide a personalized training experience.
- Detect and respond to security incidents (unauthorized access attempts, abuse).
- Diagnose and fix bugs reported by users or detected by error logging.

Data is **not** used for advertising, behavioral profiling, third-party analytics, or sold to any party.

## Authentication providers

The app uses Google Sign-In and Apple Sign-In as the only authentication methods. When you sign in:

- **Google Sign-In**: we receive your name, email address, and Google account ID from Google.
- **Apple Sign-In**: we receive your name (if you choose to share it) and a private email relay or your real email, depending on your Apple ID settings.

We do not receive your password or any other credentials from these providers. Your authentication is governed by Google's and Apple's respective privacy policies in addition to this one.

## How we share data

The app uses the following service providers as data processors:

- **Google Firebase** (authentication, database, file storage, server-side functions). Data is stored in Google Cloud regions configured for the project.
- **Cloudflare** (content delivery and edge security for video and image content). Cloudflare receives request metadata including IP address and user agent.

We do not sell, rent, or trade your data with any third party. We do not transfer data to advertising networks, analytics services, or data brokers.

## Encryption

All data transmitted between the app and our servers is encrypted in transit using HTTPS (TLS). All data stored in our backend (Firestore, Storage, Cloud Functions logs) is encrypted at rest by Google's infrastructure.

## Data retention

We retain account and activity data for as long as your account is active. Upon deletion request (see below), data is removed within 30 days. Aggregated, anonymized analytics that cannot be linked back to an individual account may be retained indefinitely. Records that we are required to retain for legal or regulatory reasons may also be kept for the period required by applicable law.

## Data deletion request

To request deletion of your account and all associated data, send an email to **[cirronox@gmail.com](mailto:cirronox@gmail.com?subject=Data%20Deletion%20Request)** with the subject line **"Data Deletion Request"**. Include the email address associated with your account so we can locate your records.

**What gets deleted:**

- Your user account and authentication record
- Profile information (name, email address, role)
- Training progress, completion records, and exercise responses
- Device identifiers associated with your account
- Security and audit logs tied to your user ID

Deletion requests are processed within 30 days of receipt. You will receive a confirmation email once the deletion is complete.

## Your rights

Depending on your jurisdiction, you may have the right to:

- Access the data we hold about you
- Correct inaccurate data
- Request deletion of your data (see above)
- Object to certain processing
- Lodge a complaint with a data protection authority

To exercise any of these rights, contact us at the email below.

## Changes to this policy

If we make material changes to this policy, we will update the "Last updated" date at the top of this document and, where required by law, notify you directly. Continued use of the app after changes take effect constitutes acceptance of the updated policy.

## Contact

For questions about this policy, your data, or to exercise any of the rights above, contact:

[cirronox@gmail.com](mailto:cirronox@gmail.com)
