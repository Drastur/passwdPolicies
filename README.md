Role Name
=========

This role covers the section 1.1-Pasword Policies of the CIS Microsoft Windows Server 2019 Benchmark v1.2.1.

Dependencies
------------
community.windows.win_security_policy.

Example Playbook
----------------
```yaml
    - name: "WinSecAutomation"
      hosts: servers
      roles:
         - role: "drastur.passwdpolicies" 
           flag: "-1.1.1--1.1.2--1.1.3--1.1.4--1.1.5--1.1.6-"
```
Author Information
------------------

Developed by Diego Ramírez Amandi as part of the TFG - Policy-driven Windows Security Automation
