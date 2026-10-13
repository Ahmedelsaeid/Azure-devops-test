# VisualSVN PowerShell Test

Run this script directly on the cloned VisualSVN server using Windows PowerShell as Administrator.

## Module-only test

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass -Force
.\Test-VisualSvnPowerShell.ps1 -OutputFolder "C:\VisualSVN-Inventory"
```

## Test repository and permission rule access

```powershell
.\Test-VisualSvnPowerShell.ps1 -OutputFolder "C:\VisualSVN-Inventory" -TestRepositoryAccess
```
