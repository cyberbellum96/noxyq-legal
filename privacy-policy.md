---
layout: default
title: NOXYQ Privacy Policy
lang: en
---


# Privacy Policy

[English](./privacy-policy.html) | [Українська](./privacy-policy-uk.html)

**NOXYQ — Network Diagnostics & Monitoring**

**Last updated: October 18, 2026**

## 1. Introduction

Welcome to NOXYQ.

NOXYQ is a network diagnostics, analysis, and monitoring platform developed under the name **NOXYQ Labs**, operated by an independent developer based in Ukraine.

We respect your privacy and are committed to protecting your personal information.

This Privacy Policy explains what information NOXYQ may access, collect, process, store, and share when you use our Android application and connected services.

**Current release: Production Guest Free 1.0.** No NOXYQ registration, sign-in, Cloud synchronization, Android Agent, advertisements, purchases or subscriptions are enabled in this release. It does not upload local scan histories to NOXYQ servers. References below to accounts, Cloud or payments describe planned capabilities only; they do not authorize those capabilities in the current release. This policy must be reviewed before they are enabled.

Optional speed measurements require the selected provider's versioned in-app disclosure and affirmative consent before discovery or measurement traffic. Declining leaves the other Free tools available. Using the app alone is not consent to an optional provider transfer.

**Contact:** noxyqlabs@gmail.com

## 2. Information We Process

Depending on which features you use, NOXYQ may process the following categories of information.

### 2.1 Network and Device Information

To provide network diagnostics, NOXYQ may access:

- Local and public IP addresses.
- Wi-Fi network names (SSID) and access point identifiers (BSSID).
- MAC addresses of discoverable network devices, when available.
- Network gateway and DNS information.
- Wi-Fi signal strength, frequencies, and channel information.
- Information about local network devices and available services.
- Network connection type and technical connection characteristics.
- Reduced cellular operator, radio and SIM-state information where Android makes it available; network overview does not read phone numbers, IMEI or IMSI.
- Network latency, packet loss, download speed, and upload speed.
- Hostnames, network ports, and diagnostic responses.

This information is processed to perform the network analysis or diagnostic operation requested by the user.

Most local network diagnostic operations are performed directly on your device.

Production Guest does not upload local scan histories or network inventory to NOXYQ Cloud. Saving local results does not create a NOXYQ account or synchronize those results with a NOXYQ server.

### 2.2 Account Information

Production Guest has no NOXYQ registration, sign-in, account or organization service. It does not request account credentials or payment details. If you voluntarily email support, the information in that correspondence is handled as described in section 9.

### 2.3 Technical and Diagnostic Information

The current Guest release has no NOXYQ Cloud/API or automatic first-party analytics/crash-upload integration. External diagnostic destinations and measurement providers receive the connection information needed for the selected operation, as described in section 5. Local Android or app-store diagnostics are subject to their own settings and policies.

### 2.4 Locally Stored Information

NOXYQ may store the following information on your device:

- Application settings and preferences.
- Local diagnostic history.
- Saved diagnostic configurations.
- Cached network information.
- Provider consent records and saved Wake-on-LAN profiles and schedules.

Local application data is generally controlled through the application and Android operating system.

Use the supported tool controls or Android app storage controls to remove local data, as described in sections 9 and 12. There is no NOXYQ Cloud history in Production Guest.

## 3. Device Permissions

NOXYQ uses Android permissions for supported diagnostic functionality. Runtime prompts depend on the Android version and selected operation.

Depending on your Android version and selected features, these permissions may include:

**Network and Internet Access**

Used to perform internet connectivity tests and communicate with selected diagnostic endpoints and network devices. NOXYQ Cloud access is disabled in the current Guest release.

**Wi-Fi and Nearby Devices**

Used to discover nearby Wi-Fi networks, inspect connection properties, and identify devices or services on the local network.

**Location Permission**

Certain Android versions require location-related permissions to access Wi-Fi scan information, including nearby access point identifiers.

NOXYQ uses such access for network diagnostics. Location-related permission does not, by itself, mean that NOXYQ continuously tracks or uploads your geographic location.

**Notifications**

The current Guest release does not use notification permission. Camera/QR enrollment is also unavailable in Production Guest.

Permissions can be managed through Android system settings. Denying a permission may limit the functionality that depends on it.

We do not request unrelated sensitive permissions solely for advertising purposes.

## 4. How We Use Information

We process information for the following purposes:

- Providing network diagnostic and monitoring features.
- Displaying Wi-Fi and network connection information.
- Performing user-requested tests and scans.
- Saving diagnostic results and application settings.
- Maintaining service reliability and security.
- Diagnosing technical problems.
- Complying with applicable legal obligations.

Current processing provides requested local diagnostics, optional provider measurements and voluntary support. Where applicable, processing is based on providing requested services, legitimate security and operational interests, consent, or legal requirements.

We do not sell personal information to data brokers or advertisers.

## 5. Network Diagnostics and Third-Party Services

Some NOXYQ features communicate with external servers to perform the diagnostic operation selected by the user.

For example:

- Ping and Traceroute send network probes to selected destinations.
- DNS tools communicate with the active network resolver; registration lookup uses HTTPS RDAP with IANA bootstrap and the selected registry.
- Speed Test communicates with selected measurement servers.
- Network discovery communicates with devices and services on the local network. iPerf, MTU and Wake-on-LAN communicate with the endpoints or devices you configure.

When a diagnostic connection is established, the destination, resolver and network operator may receive the query or probe and source IP address. Internet destinations can observe your public IP address; local-network traffic can expose local addresses.

For supported internet speed measurements, NOXYQ may use external measurement infrastructure, including **Measurement Lab (M-Lab)** or **CoverageMap**, depending on the selected provider and service availability.

These providers process measurement information under their independent policies. Opening a policy or other external link in your browser also connects to the website host, which can receive your IP address and browser information under its own practices.

Users should review applicable third-party privacy practices when using external services.

NOXYQ does not control the independent data processing practices of external diagnostic destinations.

**Important information about Speed Test providers**

Before provider discovery or measurement traffic, NOXYQ asks for the selected provider's versioned in-app consent. A matching stored consent can be reused; a changed disclosure version requires consent again. Declining avoids that speed test and leaves the other Free tools available.

CoverageMap receives connection/server requests and uploads of available test results, which can include failed tests. These include the public IP address, ISP and IP-derived location (including coordinates when returned by the service), timestamps, connection type, speed/latency measurements, test/session identifiers and general Android/WebView/application metadata. NOXYQ supplies no GPS location provider, NOXYQ account identifier, unique device identifier or Wi-Fi name. The absence of a GPS provider does not disable IP-derived location.

CoverageMap's policy describes indefinite raw measurement retention unless deleted, licensing of anonymized/aggregated datasets and uses related to its own services, including promotions. Those provider practices are independent of NOXYQ. Descriptions of CoverageMap's own app or website do not mean that NOXYQ loads that website or includes its GPS, account or advertising integrations. Provider use, retention and available deletion mechanisms follow its policy; clearing NOXYQ history does not delete provider records.

Measurement Lab (M-Lab) may collect and publicly publish technical measurement data, including the public IP address used during the test. M-Lab retains published datasets indefinitely and may not be able to delete individual test records.

Users should review the privacy policies of these providers before starting a measurement:

- [CoverageMap Privacy Policy](https://coveragemap.com/privacy-policy)
- [M-Lab Privacy Policy](https://www.measurementlab.net/privacy/)

## 6. Cloud Synchronization

NOXYQ Cloud synchronization, accounts, organizations and Android Agent are not active in Production Guest Free 1.0. Local scan results and supported histories remain on the device. If a later release changes this behavior, its data practices must be described in an updated policy before that release.

## 7. Payments and Subscriptions

Production Guest Free 1.0 has no active purchases, subscriptions or billing integration and does not request payment details. References to possible future services do not activate them in this release.

## 8. Information Sharing

Requested diagnostic traffic goes to the selected destinations, resolvers and measurement providers described in section 5. Voluntary support messages go through Gmail as described in section 9. Information we actually hold may also be disclosed where applicable law requires it or to address a legitimate security issue.

NOXYQ does not upload or sell local diagnostic histories for advertising. Independent measurement providers may use the data they receive under their own policies; this statement is not a promise about their separate processing.

## 9. Data Storage and Retention

Local settings, supported tool histories, provider consent records and saved diagnostic/Wake-on-LAN profiles remain in app-private storage until replaced or deleted. Speed Test and Wake-on-LAN histories retain up to 50 results each. This limit describes those histories, not every record or profile in the app.

Use tool history controls, delete Wake-on-LAN profiles/schedules, or clear Android app storage. Clearing speed history does not clear provider consent; clearing app storage does. Deleting a Wake-on-LAN profile removes its stored SecureOn value and schedules. Uninstalling removes local app data, subject to Android device transfer/restore behavior. Guest Free 1.0 has no NOXYQ account or Cloud history to delete.

External diagnostic services determine their own logging, retention and deletion, including M-Lab's indefinite public datasets. Provider records can differ from local history. Clearing NOXYQ data does not remove information already received or published by those providers.

If you email **noxyqlabs@gmail.com**, Gmail receives the message, sender information and associated metadata. Support correspondence is kept while needed to address the request or meet applicable obligations. You may use the same email to request access, correction or deletion of correspondence we hold. Requests are considered in relation to the information we actually hold and applicable law. Do not send passwords, tokens or SecureOn values.

## 10. Data Security

Android app-private storage protects local records; not every record is separately encrypted. Wake-on-LAN SecureOn values are stored separately using AES-GCM with an Android Keystore key. The MAC and optional SecureOn value are sent in an unencrypted UDP magic packet on an explicit wake or an enabled schedule.

DNS, discovery, probes and iPerf can use unencrypted traffic. HTTPS/WSS protect supported speed-provider and RDAP connections. There is no guarantee that every diagnostic protocol is encrypted.

Android cloud backup is disabled (allowBackup=false). Some device-to-device transfers can still include local preferences under Android rules; Keystore keys are not transferred with those preferences. Disabling cloud backup does not prevent every possible Android transfer/restore.

The reviewed Production dependency graph includes Expo, React Native, Hermes and camera support libraries, but excludes barcode ML Kit, Google Play Services scanner and Google DataTransport runtime payloads. Expo OTA updates are disabled. NOXYQ has no integrated advertising or automatic first-party analytics/crash-upload service in this release. Optional measurement-provider transfers remain active only through their described user-selected flows.

No internet-connected system can guarantee absolute security.

## 11. Your Privacy Rights and Choices

Depending on your location and applicable law, you may have rights to:

- Request access to personal information.
- Request correction of inaccurate information.
- Request deletion of personal information.
- Object to or restrict certain processing.
- Withdraw consent where processing relies on consent.
- Request a copy of certain personal information.

You may also manage supported Android permissions through your device settings.

To make a privacy-related request, contact:

**noxyqlabs@gmail.com**

We may ask for information needed to locate correspondence or verify a request. Do not send passwords, tokens or diagnostic secrets.

## 12. Account and Data Deletion

Production Guest Free 1.0 does not create NOXYQ accounts and has no account-deletion API. Use the local controls described in section 9 and on the existing [Account & Data Deletion page](./delete-account.html).

For requests concerning privacy or support correspondence, contact **noxyqlabs@gmail.com**. These requests concern information we actually hold; they do not give NOXYQ control over independent providers' datasets. A future account-enabled version would need its own applicable data controls and policy review before release; this policy does not announce such a service.

## 13. International Data Processing

NOXYQ is developed in Ukraine and may be used internationally. External measurement, website and email providers may process information in countries other than your country of residence under their own policies. Their policies explain their separate storage and transfer practices. Questions about NOXYQ's handling of support correspondence can be sent to **noxyqlabs@gmail.com**.

## 14. Children's Privacy

NOXYQ is intended for general network diagnostics and professional technical use.

The application is not specifically directed toward children under the age of 13.

We do not knowingly seek to collect personal information from children in violation of applicable law.

If you believe a child has provided personal information improperly, please contact us.

## 15. Changes to This Privacy Policy

We may update this Privacy Policy as NOXYQ develops, new features are introduced, or applicable legal requirements change.

The latest version will be made available through an accessible public page, and the date at the beginning of this document will indicate when it was last updated.

Material changes may be communicated through the application or other appropriate channels.

## 16. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or the processing of your information, please contact:

**Developer:** NOXYQ Labs  
**Application:** NOXYQ  
**Country:** Ukraine  
**Email:** noxyqlabs@gmail.com
