## MITRE ATT&CK - Mac Technique Matrix

| Persistence                  | Privilege Escalation          | Defense Evasion               | Credential Access                                     | Discovery                              | Lateral Movement                | Execution                | Collection                     | Exfiltration                                  | Command and Control                     | 
|------------------------------|-------------------------------|-------------------------------|-------------------------------------------------------|----------------------------------------|---------------------------------|--------------------------|--------------------------------|-----------------------------------------------|-----------------------------------------| 
| .bash_profile and .bashrc    | Dylib Hijacking               | Binary Padding                | [Bash History](Credential_access/Bash_history.md)     | Account Discovery                      | AppleScript                     | AppleScript              | Automated Collection           | Automated Exfiltration                        | Commonly Used Port                      | 
| Cron Job                     | Exploitation of Vulnerability | Clear Command History         | [Brute Force](Credential_access/Brute_force.md)       | Application Window Discovery           | Application Deployment Software | Command-Line Interface   | Clipboard Data                 | Data Compressed                               | Communication Through Removable Media   | 
| Dylib Hijacking              | Launch Daemon                 | Code Signing                  | Create Account                                        | File and Directory Discovery           | Exploitation of Vulnerability   | Graphical User Interface | Data Staged                    | Data Encrypted                                | Connection Proxy                        | 
| Hidden Files and Directories | Plist Modification            | Disabling Security Tools      | Credentials in Files                                  | Network Share Discovery                | Logon Scripts                   | Launchctl                | Data from Local System         | Data Transfer Size Limits                     | Custom Command and Control Protocol     | 
| LC_LOAD_DYLIB Addition       | Setuid and Setgid             | Exploitation of Vulnerability | Exploitation of Vulnerability                         | Permission Groups Discovery            | Remote File Copy                | Scripting                | Data from Network Shared Drive | Exfiltration Over Alternative Protocol        | Custom Cryptographic Protocol           | 
| Launch Agent                 | Startup Items                 | File Deletion                 | Input Capture                                         | Process Discovery                      | Remote Services                 | Source                   | Data from Removable Media      | Exfiltration Over Command and Control Channel | Data Encoding                           | 
| Launch Daemon                | Sudo                          | Gatekeeper Bypass             | Input Prompt                                          | Remote System Discovery                | Third-party Software            | Space after Filename     | Input Capture                  | Exfiltration Over Other Network Medium        | Data Obfuscation                        | 
| Launchctl                    | Valid Accounts                | HISTCONTROL                   | Keychain                                              | Security Software Discovery            |                                 | Third-party Software     | Screen Capture                 | Exfiltration Over Physical Medium             | Fallback Channels                       | 
| Login Item                   | Web Shell                     | Hidden Files and Directories  | Network Sniffing                                      | System Information Discovery           |                                 | Trap                     |                                | Scheduled Transfer                            | Multi-Stage Channels                    | 
| Logon Scripts                |                               | Hidden Users                  | Private Keys                                          | System Network Configuration Discovery |                                 |                          |                                |                                               | Multiband Communication                 | 
| Plist Modification           |                               | Hidden Window                 | Securityd Memory                                      | System Network Connections Discovery   |                                 |                          |                                |                                               | Multilayer Encryption                   | 
| Rc.common                    |                               | Indicator Removal from Tools  | Two-Factor Authentication Interception                | System Owner/User Discovery            |                                 |                          |                                |                                               | Remote File Copy                        | 
| Re-opened Applications       |                               | Indicator Removal on Host     |                                                       |                                        |                                 |                          |                                |                                               | Standard Application Layer Protocol     | 
| Redundant Access             |                               | LC_MAIN Hijacking             |                                                       |                                        |                                 |                          |                                |                                               | Standard Cryptographic Protocol         | 
| Startup Items                |                               | Launchctl                     |                                                       |                                        |                                 |                          |                                |                                               | Standard Non-Application Layer Protocol | 
| Trap                         |                               | Masquerading                  |                                                       |                                        |                                 |                          |                                |                                               | Uncommonly Used Port                    | 
| Valid Accounts               |                               | Plist Modification            |                                                       |                                        |                                 |                          |                                |                                               | Web Service                             | 
| Web Shell                    |                               | Redundant Access              |                                                       |                                        |                                 |                          |                                |                                               |                                         | 
|                              |                               | Scripting                     |                                                       |                                        |                                 |                          |                                |                                               |                                         | 
|                              |                               | Space after Filename          |                                                       |                                        |                                 |                          |                                |                                               |                                         | 
|                              |                               | Valid Accounts                |                                                       |                                        |                                 |                          |                                |                                               |                                         | 
