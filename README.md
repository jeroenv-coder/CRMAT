# CRMAT

Release downloads for a personal remote-debugging tool. This repository holds only release files (`cra-agent.exe`, `install.ps1`), no source code.

**Only run this if the owner of this tool asked you to and sent you the command.** The agent does nothing on its own:

- It needs a one-time key that the owner creates for each session; the key works once and expires after one hour.
- It shows a pair code on your screen and asks you to allow access before anything happens.
- Everything it does is shown in its window and logged on your PC.
- You stop it at any time with **Ctrl+C**; nothing stays installed.
