---
title: Upload crashes via UI
description: Upload a crash report without using our SDK, or if developing for a custom platform.
keywords: crashes, diagnostics, errors, upload
author: king-of-spades
ms.author: kegr
ms.date: 08/10/2020
ms.topic: article
ms.assetid: 7f5135ee-c133-4f1f-9376-978af1e3405d
ms.service: vs-appcenter
ms.custom: diagnostics
---

# Upload crashes via UI
If you have a native crash report from an Apple device, you can upload it via the App Center portal. The following sections will explain how to retrieve crash reports from a device and upload it to App Center.

## Retrieve crash reports from Apple devices
To retrieve crash reports from an Apple device, follow the instructions in [Apple's developer documentation](https://developer.apple.com/documentation/xcode/diagnosing_issues_using_crash_reports_and_device_logs/acquiring_crash_reports_and_diagnostic_logs).

## Manually upload crash reports via Diagnostics UI
To manually upload Apple crash reports, follow the instructions below:

1. Log into App Center and select your app.
2. In the left menu, navigate to the **Diagnostics** section.
3. On the right top corner of page, click the three dots in the upper-right corner.
4. Select **Upload Crash Log**.
5. In the Crash Upload Dialog, follow the wizard to upload your crash report.
6. Once your report is successfully uploaded, you'll see a confirmation message.

Allow some time for the report to be processed for symbolication. The crash report will appear in the Diagnostics UI after it's processed.

> [!NOTE]
> Uploading error reports retrieved from the App Center portal will lead to unpredictable results and is not supported.
> While the raw App Center text format looks similar to Apple's crash report format, it is actually a different format which is not guaranteed to be compatible.
