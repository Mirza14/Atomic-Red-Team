# Atomic-Red-Team
This threat emulation framework is to strengthen the Security Operation detection capabilities.

# Why? What is Atomic Red Team?
It can be overwhelming for security analysts to try learning every tactic, technique, and procedure (TTP) used by threat actors to test the capabilities of a Security Operations setup. That's why threat emulation frameworks were developed – they provide a structured and efficient way to simulate various techniques, making it easier for security analysts to evaluate the detection capabilities of a SOC. Many different approaches can be taken when emulating threats, and these frameworks help to organise and streamline the process.

It is an open-source project that provides a framework for performing security testing and threat emulation. It consists of tools and techniques that can be used to simulate various types of attacks and security threats, such as malware, phishing attacks, and network compromise. The Atomic Red Team aims to help security professionals assess the effectiveness of their organization's security controls and incident response processes and identify areas for improvement.
The Atomic Red Team framework is designed to be modular and flexible, allowing security professionals to select the tactics and techniques most relevant to their testing needs. It is intended to be used with other tools and frameworks, such as the MITRE ATT&CK framework, which provides a comprehensive overview of common tactics and techniques threat actors use.

# Supported Platforms:
Atomic Red Team supports emulation on a wide range of platforms, not only on known Operating Systems but also in Cloud Environments. Below is the list of platforms supported by the Atomic Red Team.

> Operating System - Windows, Linux, macOS

> Cloud Infrastructure - AWS, Azure, GCP

> Cloud Services - Office 365, Google Workspaces, Azure AD

> Others	Containers (Kubernetes)

# How Emulation Works?
In a nutshell, Atomic Red Team emulates commands that mimic threat activity using Executors. Below is the list of available executors.

> Executor = 
sh or bash - /bin/sh or /bin/bash.
OS = Linux, macOS.
Notes = Commands executed by this Executor are usually Unix tools used by threat actors for malicious intent.

> Executor =
Command Prompt - cmd.exe.
OS = Windows.
Notes = Commands executed by this Executor are usually Windows Built-in or Third-party binaries used by threat actors for malicious intent.

> Executor =
PowerShell - powershell.exe.
OS = Windows.
Notes = Emulated commands by this Executor are commonly known malicious PowerShell modules that threat actors abuse.
 
> Executor =
Manual.
OS = N/A,
Notes = The details given in this type are typically written as steps needed to be executed to emulate a threat, such as when GUI steps are involved that cannot be automated.


