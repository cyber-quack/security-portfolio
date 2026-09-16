# Windows Server and Security Home Lab

Environment: VirtualBox- Windows Server 2019 (DC), Windows 10 Clients, pfsense,
Wazuh, Kali

Self-directed lab for the purposes of obtaining hands-on experience using enterprise
IT administration and security controls.

## Contents

1. [Endpoint Protection via Group Policy](#1-endpoint-protection-via-group-policy)
2. [MFA with Entra ID](#2-mfa-with-entra-id)
3. [Network Segmentation](#3-network-segmentation)
4. [Centralized Logging with Wazuh](#4-centralized-logging-with-wazuh)


## 1. Endpoint Protection via Group Policy

<dl>
  <dt><strong>Objective:</strong></dt>
  <dd>Use Group Policy to enforce antivirus settings on all lab computers, so individual users can't turn protection off. Then test it by dropping a harmless fake virus file on a client machine and watch Defender catch it.</dd>
</dl>