# Exit-PpModuleNotFound
Module: Capa.PowerShell.Module.PowerPack.Exit

Set error code that the module was not found.

## Syntax

```powershell
Exit-PpModuleNotFound
	-ExitMessage <String>
```

## Description

Uses the Exit-PpScript that comes from PSlib.psm1, to set the package error.

## Examples

### Example 1
```powershell
Exit-PpModuleNotFound
```
    
### Example 2
```powershell
Exit-PpModuleNotFound -ExitMessage 'Test where I set ExitMessage'
```
    

## Parameters

-**ExitMessage**


| Name | Value |
| ---- | ---- |
| Type: | String |
| Position: | 1 | 
| Default value: | None | 
| Accept pipeline input: | false | 
| Accept wildcard characters: | false | 


## Notes

Custom command.