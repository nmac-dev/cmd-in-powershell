# cmd-in-powershell

## Purpose

cmd-in-powershell attempts to provide minor alterations to certain commands in powershell for a smoother DevEx experience.

**Issues to resolve**:

 - Not all Command Prompt commands function the same in powershell.
 - `git-bash` commands (i.e. `grep`) not being available in powershell.
 - Powershell commands not working as intended:
   - ◻️ `where` does not work unless you exactly call `where.exe` (Windows 11 issue)
   - ◻️ `mklink` "not recognized as the name of a cmdlet"
