# cmd-in-powershell

## Purpose

cmd-in-powershell attempts to provide minor alterations to certain commands in powershell for a smoother DevEx experience.

**Issues to resolve**:

 - Not all Command Prompt commands function the same in powershell.
   - ◻️ `mklink` "not recognized as the name of a cmdlet"

### Bash

`git-bash` commands (i.e. `grep`) not being available in powershell:

#### Utility

 - ◻️ `grep`
 - ◻️ `awk`
 - ◻️ `sed`
 - ◻️ `ls`
 - ◻️ `cat`
 - ◻️ `echo`
 - ◻️ `find`
 - ◻️ `xargs`
 - ◻️ `sort`
 - ◻️ `uniq`
 - ◻️ `cut`

#### Files

 - ◻️ `cp`
 - ◻️ `mv`
 - ◻️ `rm`
 - ◻️ `mkdir`
 - ◻️ `rmdir`
 - ◻️ `touch`

#### Processs

 - ◻️ `ps`
 - ◻️ `kill`
 - ◻️ `jobs`
 - ◻️ `bg`
 - ◻️ `fg`

#### Network

 - ◻️ `curl`
 - ◻️ `wget`
 - ◻️ `ssh`
 - ◻️ `scp`

#### Compression

 - ◻️ `tar`
 - ◻️ `gzip`
 - ◻️ `bzip2`
 - ◻️ `zip`
 - ◻️ `unzip`

#### Version-Control

 - ◻️ `git`
 - ◻️ `gitk`

#### Editors

 - ◻️ `vim`
 - ◻️ `nano`

#### Shell

 - ◻️ `bash`
 - ◻️ `sh`

 - Powershell commands not working as intended:
   - ◻️ `where` does not work unless you exactly call `where.exe` (Windows 11 issue)
