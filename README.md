# Pythonic Arsenal

Welcome to the Pythonic Arsenal! This repository houses a comprehensive collection of Python scripts designed to support various cybersecurity objectives, from pre-attack reconnaissance to achieving impact.

## About the Creator

The Pythonic Arsenal was created by AniketKadam, a passionate cybersecurity enthusiast with years of experience in offensive and defensive security operations. AniketKadam is dedicated to providing practical and effective automation solutions to empower cybersecurity professionals in their mission to protect digital assets and defend against cyber threats.

For any inquiries, feedback, or collaboration opportunities, feel free to reach out to AniketKadam via email at cybernaut.ani@gmail.com

Feel free to explore and utilize these Python scripts for your cybersecurity objectives! If you have any questions or suggestions, please don't hesitate to reach out to [Creator's Name]. Happy scripting!

## Pre-ATT&CK Objectives

- **PortScan.py**: Script for port scanning to identify active services.
- **HoneyScan.py**: Script for detecting and monitoring honey pot services.
- **DNSExploration.py**: Script for DNS exploration to gather information about domain names.
  - **dns_search.txt**: Sample DNS search output file.
- **HoneyResolver.py**: Script for resolving DNS queries in a honey pot environment.

## Gaining Initial Access

- **TestDefaultCredentials.py**: Script for testing default credentials against target systems.
  - **defaults.txt**: List of default credentials.
- **ValidAccountDetection.py**: Script for detecting valid user accounts.
  - **allowlist.txt**: Allowlist of valid user accounts.
  - **defaults.txt**: List of default credentials.
- **AutorunSetup.py**: Script for setting up autorun functionality using malicious payloads.
  - **Firefox.ico**: Icon file.
  - **malicious.py**: Sample malicious payload.
- **AutorunDetection.py**: Script for detecting autorun setups.

## Achieving Code Execution

- **WMIExecution.py**: Script for executing code using Windows Management Instrumentation (WMI).
- **WMIDetection.py**: Script for detecting WMI executions.
- **TaskScheduler.py**: Script for interacting with Windows Task Scheduler.
- **ScheduleTracker.py**: Script for tracking changes in scheduled tasks.

## Maintaining Persistence

- **RegAutorun.py**: Script for adding entries to the Windows Registry for autorun.
  - **BuildExe.py**: Script for building executable files.
  - **Firefox.ico**: Icon file.
  - **malicious.py**: Sample malicious payload.
- **DetectRegistryAutorun.py**: Script for detecting registry autorun entries.
- **ChangePath.py**: Script for modifying system paths.
- **DetectPathModificationRegistry.py**: Script for detecting modifications to system paths in the registry.
- **DetectPathModificationEvent.py**: Script for detecting modifications to system paths using event monitoring.

## Performing Privilege Escalation

- **LogonScript.py**: Script for executing commands through logon scripts.
- **DetectLogonScript.py**: Script for detecting logon script executions.
- **win32evtlog.py**: Utility module for interacting with Windows event logs.
  - **test.py**: Test script for event log detection.
- **PythonLibraryMismatch.py**: Script for detecting Python library mismatches.

## Evading Defenses

- **DetectAntivirusService.py**: Script for detecting antivirus services.
- **TerminateAntivirus.py**: Script for terminating antivirus processes.
- **DecoyProcess.py**: Script for creating decoy processes.
- **AlternateDataStreams.py**: Script for interacting with alternate data streams.
- **DetectADS.py**: Script for detecting alternate data streams.

## Accessing Credentials

- **ChromeDump.py**: Script for extracting credentials from Google Chrome.
- **DetectLocalStateAccess.py**: Script for detecting unauthorized access to Google Chrome's local state file.
- **NetworkCredentialSniffing.py**: Script for sniffing network traffic for credentials.
  - **merged.pcap**: Sample packet capture file.
- **DecoyCredentials.py**: Script for generating decoy credentials.

## Performing Discovery

- **UserDiscovery.py**: Script for discovering user accounts on a system.
- **LastLogin.py**: Script for retrieving last login information for users.
- **DetectAdminLogin.py**: Script for detecting administrator logins.
- **FileDiscovery.py**: Script for discovering files on a system.
  - **clients.csv**: Sample CSV file.
  - **Resume.docx**: Sample Word document.
- **MonitorDecoyContent.py**: Script for monitoring decoy content changes.
- **CreateDecoyContent.py**: Script for creating decoy content.
  - **clients.csv**: Sample CSV file.
  - **Resume.docx**: Sample Word document.

## Moving Laterally

- **RemoteServices.py**: Script for interacting with remote services.
  - **malicious.py**: Sample malicious script.
- **DetectSMB.py**: Script for detecting Server Message Block (SMB) activity.
  - **SMB.pcapng**: Sample SMB packet capture file.
- **WebSessionCookieHijack.py**: Script for hijacking web session cookies.
- **CreateFakeCookie.py**: Script for creating fake web session cookies.
  - **CookieCleanup.py**: Script for cleaning up cookies.
- **DetectDecoyCookies.py**: Script for detecting decoy cookies.
  - **decoyCookie.pcap**: Sample packet capture file.

## Collecting Intelligence

- **ModifyClipboard.py**: Script for modifying clipboard contents.
- **MonitorClipboard.py**: Script for monitoring clipboard activity.
- **LocalEmailFiles.py**: Script for accessing local email files.
  - **sample.pst**: Sample Outlook Personal Storage Table (PST) file.
- **FindEmailArchives.py**: Script for finding email archive files.

## Implementing Command and Control

- **EncryptedChannelClient.py**: Script for implementing an encrypted communication channel (client).
- **EncryptedChannelServer.py**: Script for implementing an encrypted communication channel (server).
- **DetectEncryptedTraffic.py**: Script for detecting encrypted traffic.
  - **EncryptedChannel.pcapng**: Sample encrypted traffic packet capture file.
- **ProtocolTunnelingClient.py**: Script for implementing protocol tunneling (client).
- **ProtocolTunnelingServer.py**: Script for implementing protocol tunneling (server).
- **ProtocolDecoder.py**: Script for decoding tunneled protocols.

## Exfiltrating Data

- **DNSExfiltrationClient.py**: Script for exfiltrating data using DNS.
- **DNSExfiltrationServer.py**: Script for receiving exfiltrated data via DNS.
- **DetectAlternativeProtocol.py**: Script for detecting alternative data exfiltration protocols.
- **NonApplicationClient.py**: Script for exfiltrating data using non-application protocols (client).
- **NonApplicationServer.py**: Script for receiving exfiltrated data via non-application protocols (server).
- **DetectNonApplicationProtocol.py**: Script for detecting non-application data exfiltration.

## Achieving Impact

- **DataEncryption.py**: Script for encrypting data.
  - **Resume.docx**: Sample Word document.
- **CheckFileEntropies.py**: Script for checking file entropies.
  - **Resume.docx**: Sample Word document.
- **AccountAccessRemoval.py**: Script for removing account access.
- **DetectPasswordChange.py**: Script for detecting password changes.

---

Feel free to explore and utilize these Python scripts for your cybersecurity objectives! If you have any questions or suggestions, please don't hesitate to reach out to us. Happy scripting!
