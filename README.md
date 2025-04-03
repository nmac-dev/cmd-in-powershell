# cmd-in-powershell

## Purpose

cmd-in-powershell attempts to provide minor alterations to certain commands in powershell for a smoother DevEx experience.

## Issues to resolve


### Command Prompt

---

Not all Command Prompt commands function the same in powershell.

 - ✅ `mklink` "not recognized as the name of a cmdlet"
 - ✅ `set`
 - ◻️ `setx`


### Bash

---

`git-bash` commands (i.e. `grep`) not being available in powershell:

#### Utility

 - ✅ `grep`
 - ✅ `awk`
 - ✅ `sed`
 - ◻️ `ls`
 - ◻️ `cat`
 - ◻️ `echo`
 - ◻️ `find`
 - ✅ `xargs`
 - ✅ `sort`
 - ✅ `uniq`
 - ✅ `cut`

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

 - ✅ `tar`
 - ✅ `gzip`
 - ✅ `bzip2`
 - ✅ `zip`
 - ✅ `unzip`

#### Version-Control

 - ◻️ `git`
 - ◻️ `gitk`

#### Editors

 - ✅ `vim`
 - ✅ `nano`

#### Shell

 - ◻️ `bash`
 - ◻️ `sh`


### Powershell

---

Powershell commands not working as intended:

#### Fixes

 - ❌ `where` does not work unless you exactly call `where.exe` (Windows 11 issue)
    - Cannot override alias conflict

#### Custom Commands
 - ◻️ `todo` found in [CFG](https://github.com/nmac-dev/cfg) reposistory
