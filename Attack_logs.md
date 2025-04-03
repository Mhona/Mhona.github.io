| Event ID | Timestamp           | Description                                                                | Log Type | Relevance to Attack |
|----------|---------------------|----------------------------------------------------------------------------|----------|---------------------|
| 4625     | 03/27/2025 09:44:57 AM | An account failed to log on. User: Jennifer Thompson, Source IP: 192.168.1.115, Failure Reason: Unknown user name or bad password | Security | Yes |
| 4625     | 03/27/2025 09:46:05 AM | An account failed to log on. User: Jennifer Thompson, Source IP: 192.168.1.123, Failure Reason: Unknown user name or bad password | Security | Yes |
| 4624     | 03/27/2025 09:47:26 AM | An account was successfully logged on. User: Jennifer Thompson, Source IP: 192.168.1.126, Logon Type: 3 (Network) | Security | Yes |
| 4672     | 03/27/2025 09:47:54 AM | Special privileges assigned to new logon. User: Jennifer Thompson, Privileges: SeBackupPrivilege | Security | Yes |
| 4688     | 03/27/2025 09:49:04 AM | A new process has been created. Process Name: powershell.exe, Parent Process: explorer.exe, User: Jennifer Thompson | System | Yes |
| 4688     | 03/27/2025 09:50:16 AM | A new process has been created. Process Name: suspicious.exe, Parent Process: powershell.exe, User: Jennifer Thompson | System | Yes |
| 5156     | 03/27/2025 09:50:34 AM | The Windows Filtering Platform has permitted a connection. Source IP: 192.168.1.127, Logon Type: 3 (Network) | Security | Yes |
| 1116     | 03/27/2025 09:52:14 AM | Microsoft Defender detected malware. File: suspicious.exe, Action: Quarantined, Threat: Ransomware.Generic | Application | Yes |
| 4688     | 03/27/2025 09:52:39 AM | A new process has been created. Process Name: cmd.exe, Parent Process: suspicious.exe, User: Jennifer Thompson | System | Yes |
| 4697     | 03/27/2025 09:53:38 AM | A service was installed in the system. Service Name: EvilService, Executable: C:\Temp\evil.exe, User: Jennifer Thompson | Security | Yes |
| 7045     | 03/27/2025 09:55:07 AM | A service was installed in the system. Service Name: EvilService, Image Path: C:\Temp\evil.exe, Service Type: User Mode | System | Yes |
| 4663     | 03/27/2025 09:55:35 AM | An attempt was made to access an object. Object: C:\Data\budget.xlsx, User: Jennifer Thompson, Access: Read | Security | Yes |
| 4663     | 03/27/2025 09:56:39 AM | An attempt was made to access an object. Object: C:\Data\budget.xlsx, User: Jennifer Thompson, Access: Write | Security | Yes |
| 4688     | 03/27/2025 09:58:10 AM | A new process has been created. Process Name: rundll32.exe, Parent Process: cmd.exe, User: Jennifer Thompson | System | Yes |
| 5156     | 03/27/2025 09:59:03 AM | The Windows Filtering Platform has permitted a connection. Source IP: 192.168.1.137, Logon Type: 3 (Network) | Security | Yes |
| 1117     | 03/27/2025 09:59:41 AM | Microsoft Defender removed malware. File: suspicious.exe, Action: Cleaned, Threat: Ransomware.Generic | Application | Yes |
| 4698     | 03/27/2025 10:01:28 AM | A scheduled task was created. Task Name: EvilTask, Executable: C:\Temp\evil.exe, User: Jennifer Thompson | Security | Yes |
| 5145     | 03/27/2025 10:01:32 AM | A network share object was checked for access. Share Name: \\SERVER\Shared, User: Jennifer Thompson, Access: Write | Security | Yes |
| 4656     | 03/27/2025 10:03:04 AM | A handle to an object was requested. Object: C:\System32\config\SAM, User: Jennifer Thompson, Access: Read | Security | Yes |
| 4672     | 03/27/2025 10:04:16 AM | Special privileges assigned to new logon. User: Jennifer Thompson, Privileges: SeDebugPrivilege | Security | Yes |
