# SoniQL: Speedy MSSQL Enumeration and Exploitation built espeically as part of the OSEP course

SoniQL is an ultra-fast tool designed for offensive security professionals, specifically red teamers, penetration testers, and ethical hackers. It is built with a single goal in mind: speed. SoniQL excels in quickly discovering, interacting with, and exploiting MSSQL servers within a domain. With its streamlined workflow, you can efficiently perform enumeration, privilege escalation, and exploitation tasks, saving precious time during assessments.

# Usage
Just download the executable, run it and connect to the MSSQL server instance and get mess around.

# Key Features
1. Impersonating as LOGIN (SA) on the connected server and get command execution in two ways: xp_cmdshell or sp_oamethod.
2. Impersonating as USER (dbo) on the connected server and get command execution in two ways: xp_cmdshell or sp_oamethod.
3. Connect to a linked servers, enable xp_cmdshell and get command execution on the linked servers.

# ToDo
1. Add xp_dirtree option?
