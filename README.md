# Remove Windows 10 and Windows 11 Bloat

- Launch **PowerShell**.
- **Enable** running a PowerShell script file
  - ```Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser```
- Download the "**RemoveBloat.ps1**" file.
- Run the file inside the **PowerShell**.
- **Disable** running any PowerShell script file - it's important to disable it after running the PowerShell script to remove all the bloatware
  - ```Set-ExecutionPolicy -ExecutionPolicy Undefined -Scope CurrentUser```

