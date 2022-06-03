---
title: Admin Quarantine
pcx-content-type: how-to
weight: 7
---

# Admin Quarantine

Admin Quarantine allows you to automatically prevent incoming messages from reaching a recipient's inbox based on the [disposition](/email-security/reference/dispositions-and-attributes/) assigned by Area 1.

The messages sent to Admin Quarantine are determined by your [domain settings](/email-security/email-configuration/domains-and-routing/domains/).

## Access Admin Quarantine

To view and potentially release emails from the **Admin Quarantine**, log in to the [Area 1 dashboard](https://horizon.area1security.com/) and go to **Email** > **Admin Quarantine**.

You can view all quarantined emails as needed.

## Release quarantined emails

From **Admin Quarantine**, you can also release quarantined emails by selecting one or more messages and then clicking **...** > **Release**.

These email messages will then by sent to the original recipients from `quarantine@area1reports.com` with the original message attached in a zip file.