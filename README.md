<div align="center">
<a href="https://github.com/FreeCoderExperience/SecuriNET">
  <img src="https://raw.githubusercontent.com/FreeCoderExperience/SecuriNET/main/images/logotransparentv1.png" alt="SecuriNET" width="300">
</a>

SecuriNET is a comprehensive network security application designed for Windows systems, providing robust monitoring, firewall management, and access control tools. Its intuitive interface allows both IT professionals and traditional users to maintain a secure environment while keeping track of network activity in real-time. __SecuriNET__ is designed to be both user-friendly and powerful, helping users maintain control over their network security. Whether you’re securing a home network or monitoring multiple endpoints in a small business environment, SecuriNET provides the tools to stay informed, block threats, and maintain peace of mind.


[Installation](https://github.com/FreeCoderExperience/SecuriNET/#installation) - [FAQ](https://github.com/FreeCoderExperience/SecuriNET/#frequently-asked-questions) - [Documentation](https://github.com/FreeCoderExperience/SecuriNET/documentation) - [Report a Bug](https://github.com/FreeCoderExperience/SecuriNET/issues)

[![Version](https://img.shields.io/github/v/release/FreeCoderExperience/SecuriNET?label=Version)](https://github.com/FreeCoderExperience/SecuriNET/releases)
![C#](https://img.shields.io/github/languages/top/FreeCoderExperience/SecuriNET?color=blue&label=C%23)
![XAML](https://img.shields.io/github/languages/top/FreeCoderExperience/SecuriNET?color=purple&label=XAML)
![JavaScript](https://img.shields.io/github/languages/top/FreeCoderExperience/SecuriNET?color=yellow&label=JavaScript)
![Cloudflare](https://img.shields.io/badge/Cloudflare-5%25-orange)

In order to use SecuriNET, you must create an account in the app. Account verification is performed via Cloudflare to ensure that access to the application’s security features is protected and you are secure.

</div>

<hr style="height:4px; background-color:black; border:none;">

## Features

__1. Firewall Management__

- View and manage inbound and outbound firewall rules for Domain, Private, and Public profiles.
- Create, edit, and delete custom firewall rules with ease.
- Export firewall rules to CSV for auditing or backup.
- Block or unblock IPs directly from the event log.

__2. Connection Monitoring__

- Real-time monitoring of active TCP connections.
- Logs suspicious connection attempts, including source IP, country, and threat assessment.
- Automatically blocks malicious IPs based on configurable rules.
- Provides visual graphs of connection history and threat levels per IP.

__3. Port & Service Awareness__

- Detects open TCP/UDP ports with service mapping.
- Displays a summary of active ports and connected endpoints.
- Allows custom configuration of port mappings for better visibility.

__4. Remote Access Control__

- Enable or disable RDP (Remote Desktop Protocol) and SSH services safely.
- Automatically adjusts firewall rules when toggling RDP/SSH.
- Provides quick status updates for remote access services.
- Allows remote Login-type connection blocking such as NTLM, RDP, and SSH.

__5. System & Network Insights__

- Displays system uptime, logged-in users, CPU cores, and local IP addresses.
- Dashboard tiles update dynamically to reflect real-time network and firewall stats.

__6. Update Management__

- Automatic update feature with configurable maintenance windows.
- Option to manually trigger updates at any time.
- Ensures the application stays up-to-date with minimal intervention.

__7. Customizable Interface__

- Dark mode and light mode toggle for user preference.
- 12-hour and 24-hour time format support.
- Clean, modern, and interactive dashboard for easy navigation between Firewall, Dashboard, Updates, and Settings.

__8. Event Logging & Incident Response__

- Maintains a history of suspicious events.
- Provides detailed IP information including organization, threat score, and total connections.
- Supports copying IP addresses directly from the interface for quick action.


## ❓ __Frequently Asked Questions__

### __1. Is SecuriNET free to use?__
Yes. __SecuriNET is free to use__, with all core security and monitoring features available at no cost.

---

### __2. What platforms does SecuriNET support?__
SecuriNET currently supports __Windows-based systems__ only.

---

### __3. Do I need administrator privileges to run SecuriNET?__
__Yes.__ Administrator privileges are required to manage firewall rules, monitor network activity, and control system-level services.

---

### __4. Can SecuriNET modify Windows Firewall settings?__
__Yes.__ SecuriNET integrates directly with __Windows Defender Firewall__ to create, manage, and remove firewall rules according to your preference.

---

### __5. Can SecuriNET automatically block suspicious connections?__
Yes. When blocking is enabled, __suspicious or malicious activity can be detected and blocked automatically__.

---

### __6. Is my data sent to the cloud or stored locally?__
Most operational data is stored __locally on your system__. Limited account verification data is securely processed via cloud services when required.

---

### __7. What do I need to create an account to use SecuriNET?__
An account is required to __ensure secure and authorized access__ to SecuriNET’s features and prevent misuse. All you need is to create a username and password.

---

### __8. Does SecuriNET support Remote Desktop (RDP) and SSH management?__
__Yes.__ SecuriNET allows you to __enable or disable RDP and SSH__ directly from the application when supported by the system.

---

### __9. How often does SecuriNET check for updates?__
SecuriNET supports __automatic updates__, which can be configured within a user-defined maintenance window.

---

### __10. Where can I report bugs or request new features?__
Please submit issues, bug reports, or feature requests via __GitHub Issues__ in the project repository.

## __Installation__

You can install SecuriNET using one of the following methods:

__1. Download the latest release__

1. Download the latest release from [Releases](https://github.com/FreeCoderExperience/SecuriNET/releases).
2. Download the ZIP file for the latest version.
3. Extract the ZIP and run `SecuriNET.exe`.

Note: Administrator privileges are required for firewall and network operations.

__2. Clone the repository with Git__

```bash
git clone https://github.com/FreeCoderExperience/SecuriNET.git
cd SecuriNET
```

__3. Download using cURL__

```bash
curl -LO https://github.com/FreeCoderExperience/SecuriNET/archive/refs/heads/main.zip
unzip main.zip
cd SecuriNET-main
```

After extracting or cloning, run SecuriNET.exe as an administrator to enable all features.

## __Usage & Documentation__

For detailed instructions on how to use __SecuriNET__, including setup, configuration, and troubleshooting, please refer to the official documentation. All the information you need to get started and make the most of the application can be found here: [Documentation↗](https://github.com/FreeCoderExperience/SecuriNET/documentation).

For further questions, feedback, or support, please open an issue or discussion directly on the GitHub repository. The community and maintainers will be happy to assist. 

## __Contributors__

We welcome contributions, including feedback, feature requests, and suggestions. Please share your input by submitting an issue or a pull request on the [GitHub repository↗](https://github.com/FreeCoderExperience/SecuriNET/issues).

## __License__

__SecuriNET__ is currently released as proprietary free software.
The source code is not open source.

Future versions may be released under a different license and may be made open source (if the community so wishes).
