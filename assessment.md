# LogHawk Security Log Assessment

Generated: 2026-11-25 14:11

Entries assessed: 20

- **BENIGN** This is a standard audit event indicating legitimate enumeration of stored credentials by the logged-in user frank, which is a normal behavior for credential management.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This log entry records a legitimate read/enumerate operation on Credential Manager by the logged-in user frank, which is a standard user activity with no indicators of compromise.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This is a standard audit event indicating a legitimate enumeration of stored Credential Manager credentials by an authenticated user, which is expected behavior under normal operations.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** The log shows a legitimate read/enumerate operation on Credential Manager by an authorized local user (frank) on their own machine, which is normal behavior for credential management tasks.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** The log indicates a legitimate enumeration of stored credentials by an authenticated local user, which is expected behavior during routine credential access and matches documented Microsoft event 5379 activity.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This event logs a legitimate read/enum operation on Credential Manager credentials by an authenticated local user, which is normal behavior unless unusual context (e.g., high frequency, unusual user) is present.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This event logs a routine user read operation (enumerate credentials) in Credential Manager, which is a legitimate Windows activity when accessing stored credentials legitimately.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This is a routine, audited operation where the user "frank" legitimately enumerated credentials stored in Credential Manager, indicating normal system behavior without signs of abuse or attack.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** The log shows a legitimate user reading stored credentials in Credential Manager, which is a standard, non-malicious operation when authorized.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** The log entry indicates a legitimate read operation (enumerate credentials) on Credential Manager by the local user frank, which is normal behavior when accessing stored credentials.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This event logs a normal system-level enumeration of stored credentials by the local SYSTEM account, which is expected behavior during routine credential access operations.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		SYSTEM
	Account Name:		DESKTOP-M75JPLR$
	Account Domain:		WORKGROUP
	Logon ID:		0x3E7
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** The log shows a system account (SYSTEM) enumerating Credential Manager credentials, which is a legitimate internal operation typically performed by system processes or authorized tools.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		SYSTEM
	Account Name:		DESKTOP-M75JPLR$
	Account Domain:		WORKGROUP
	Logon ID:		0x3E7
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** The log entry indicates a legitimate enumeration of Credential Manager credentials by the local SYSTEM account, which is a normal administrative operation with no signs of unauthorized access or malicious intent.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		SYSTEM
	Account Name:		DESKTOP-M75JPLR$
	Account Domain:		WORKGROUP
	Logon ID:		0x3E7
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** The log shows a legitimate read operation (enumerate credentials) by a local user on their own Credential Manager store, which is expected behavior with no indicators of abuse.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This event logs a legitimate user (frank) enumerating credentials in Credential Manager, which is a normal administrative or user task and does not indicate malicious activity.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** This is a normal audit event indicating a legitimate user (frank) enumerated stored credentials in Credential Manager, which is expected behavior during routine access.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 5379 | User Account Management | Credential Manager credentials were read.

Subject:
	Security ID:		DESKTOP-M75JPLR\frank
	Account Name:		frank
	Account Domain:		DESKTOP-M75JPLR
	Logon ID:		0x54BDE562
	Read Operation:		Enumerate Credentials

This event occurs when a user performs a read operation on stored credentials in Credential Manager.`
- **BENIGN** Event ID 4672 with SYSTEM as the subject and assignment of standard system privileges (e.g., SeDebugPrivilege, SeImpersonatePrivilege) is a normal part of Windows startup or system service initialization.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 4672 | Special Logon | Special privileges assigned to new logon.

Subject:
	Security ID:		SYSTEM
	Account Name:		SYSTEM
	Account Domain:		NT AUTHORITY
	Logon ID:		0x3E7

Privileges:		SeAssignPrimaryTokenPrivilege
			SeTcbPrivilege
			SeSecurityPrivilege
			SeTakeOwnershipPrivilege
			SeLoadDriverPrivilege
			SeBackupPrivilege
			SeRestorePrivilege
			SeDebugPrivilege
			SeAuditPrivilege
			SeSystemEnvironmentPrivilege
			SeImpersonatePrivilege
			SeDelegateSessionUserImpersonatePrivilege`
- **BENIGN** This event represents a legitimate system-level logon (Logon Type 5 = Service logon) initiated by the SYSTEM account via services.exe, which is a normal Windows behavior for internal service operations.
  - `Audit Success | 11/25/2026 2:06:40 PM | Microsoft-Windows-Security-Auditing | 4624 | Logon | An account was successfully logged on.

Subject:
	Security ID:		SYSTEM
	Account Name:		DESKTOP-M75JPLR$
	Account Domain:		WORKGROUP
	Logon ID:		0x3E7

Logon Information:
	Logon Type:		5
	Restricted Admin Mode:	-
	Remote Credential Guard:	-
	Virtual Account:		No
	Elevated Token:		Yes

Impersonation Level:		Impersonation

New Logon:
	Security ID:		SYSTEM
	Account Name:		SYSTEM
	Account Domain:		NT AUTHORITY
	Logon ID:		0x3E7
	Linked Logon ID:		0x0
	Network Account Name:	-
	Network Account Domain:	-
	Logon GUID:		{00000000-0000-0000-0000-000000000000}

Process Information:
	Process ID:		0x540
	Process Name:		C:\Windows\System32\services.exe

Network Information:
	Workstation Name:	-
	Source Network Address:	-
	Source Port:		-

Detailed Authentication Information:
	Logon Process:		Advapi  
	Authentication Package:	Negotiate
	Transited Services:	-
	Package Name (NTLM only):	-
	Key Length:		0

This event is generated when a logon session is created. It is generated on the computer that was accessed.

The subject fields indicate the account on the local system which requested the logon. This is most commonly a service such as the Server service, or a local process such as Winlogon.exe or Services.exe.

The logon type field indicates the kind of logon that occurred. The most common types are 2 (interactive) and 3 (network).

The New Logon fields indicate the account for whom the new logon was created, i.e. the account that was logged on.

The network fields indicate where a remote logon request originated. Workstation name is not always available and may be left blank in some cases.

The impersonation level field indicates the extent to which a process in the logon session can impersonate.

The authentication information fields provide detailed information about this specific logon request.
	- Logon GUID is a unique identifier that can be used to correlate this event with a KDC event.
	- Transited services indicate which intermediate services have participated in this logon request.
	- Package name indicates which sub-protocol was used among the NTLM protocols.
	- Key length indicates the length of the generated session key. This will be 0 if no session key was requested.`
- **BENIGN** This log event records the expected assignment of high-privilege tokens to the SYSTEM account during a normal Windows logon, which is standard behavior for system processes.
  - `Audit Success | 11/25/2026 2:03:04 PM | Microsoft-Windows-Security-Auditing | 4672 | Special Logon | Special privileges assigned to new logon.

Subject:
	Security ID:		SYSTEM
	Account Name:		SYSTEM
	Account Domain:		NT AUTHORITY
	Logon ID:		0x3E7

Privileges:		SeAssignPrimaryTokenPrivilege
			SeTcbPrivilege
			SeSecurityPrivilege
			SeTakeOwnershipPrivilege
			SeLoadDriverPrivilege
			SeBackupPrivilege
			SeRestorePrivilege
			SeDebugPrivilege
			SeAuditPrivilege
			SeSystemEnvironmentPrivilege
			SeImpersonatePrivilege
			SeDelegateSessionUserImpersonatePrivilege`
- **BENIGN** This is a standard system-level logon (Logon Type 5, Service logon) performed by the SYSTEM account via services.exe, which is a normal Windows behavior for service initialization and not indicative of malicious activity.
  - `Audit Success | 11/25/2026 2:03:04 PM | Microsoft-Windows-Security-Auditing | 4624 | Logon | An account was successfully logged on.

Subject:
	Security ID:		SYSTEM
	Account Name:		DESKTOP-M75JPLR$
	Account Domain:		WORKGROUP
	Logon ID:		0x3E7

Logon Information:
	Logon Type:		5
	Restricted Admin Mode:	-
	Remote Credential Guard:	-
	Virtual Account:		No
	Elevated Token:		Yes

Impersonation Level:		Impersonation

New Logon:
	Security ID:		SYSTEM
	Account Name:		SYSTEM
	Account Domain:		NT AUTHORITY
	Logon ID:		0x3E7
	Linked Logon ID:		0x0
	Network Account Name:	-
	Network Account Domain:	-
	Logon GUID:		{00000000-0000-0000-0000-000000000000}

Process Information:
	Process ID:		0x540
	Process Name:		C:\Windows\System32\services.exe

Network Information:
	Workstation Name:	-
	Source Network Address:	-
	Source Port:		-

Detailed Authentication Information:
	Logon Process:		Advapi  
	Authentication Package:	Negotiate
	Transited Services:	-
	Package Name (NTLM only):	-
	Key Length:		0

This event is generated when a logon session is created. It is generated on the computer that was accessed.

The subject fields indicate the account on the local system which requested the logon. This is most commonly a service such as the Server service, or a local process such as Winlogon.exe or Services.exe.

The logon type field indicates the kind of logon that occurred. The most common types are 2 (interactive) and 3 (network).

The New Logon fields indicate the account for whom the new logon was created, i.e. the account that was logged on.

The network fields indicate where a remote logon request originated. Workstation name is not always available and may be left blank in some cases.

The impersonation level field indicates the extent to which a process in the logon session can impersonate.

The authentication information fields provide detailed information about this specific logon request.
	- Logon GUID is a unique identifier that can be used to correlate this event with a KDC event.
	- Transited services indicate which intermediate services have participated in this logon request.
	- Package name indicates which sub-protocol was used among the NTLM protocols.
	- Key length indicates the length of the generated session key. This will be 0 if no session key was requested.`
