<div align="center">

# This repository is a copy
Go at [FULU Foundation's repo](https://github.com/FULU-Foundation/OrcaSlicer-bambulab) for a more up-to-date version













## This version of OrcaSlicer restores full BambuNetwork support for Bambu Lab printers.

You are not limited to LAN only.  
It works over the internet just like before, through BambuNetwork, with full functionality for normal use and printing.

## Installation

### Windows

Windows requires WSL 2.

Before first launch, open Command Prompt or PowerShell as Administrator and run:

```bat
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

Restart Windows, then launch Orca Studio.

### Linux

On Linux, a normal installation is enough.

### macOS

Work in progress.


## BMCU

I also encourage you to use BMCU.

You can find BMCU firmware in my repositories.

</div>
