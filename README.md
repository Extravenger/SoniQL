# SoniQL: Speedy MSSQL Enumeration and Exploitation (OSEP Edition)

SoniQL is an ultra-fast tool designed specifically for offensive security professionals, including red teamers, penetration testers, and ethical hackers. Built with speed as its core objective, SoniQL enables quick discovery, interaction, and exploitation of MSSQL servers within a domain. Whether you're performing enumeration, privilege escalation, or exploitation, SoniQL's streamlined process helps you save time during assessments—making it the perfect tool for real-world red team operations, especially as part of the OSEP course.
Key Features:

# Impersonation and Command Execution:
- Impersonate as a LOGIN (e.g., SA) on a connected MSSQL server and achieve command execution via xp_cmdshell or sp_oamethod.
- Impersonate as a USER (e.g., dbo) on a connected MSSQL server and gain command execution through xp_cmdshell or sp_oamethod.
- Linked Server Access: Connect to linked MSSQL servers, enable xp_cmdshell, and execute commands remotely on those servers.

# Usage:

- Simply download the executable, connect to the MSSQL instance, and start interacting with the server. From there, you can easily enumerate, escalate privileges, and exploit the system.

# ToDo:

    xp_dirtree option (planned for future release).
