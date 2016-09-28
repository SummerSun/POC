---
external help file: SMAzure_Compute.xml
online version: 
schema: 2.0.0
updated_at: 9/8/2016 10:40 AM
ms.date: 9/8/2016
ms.topic: reference
content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v0.9.8/Start-AzureEmulator.md
original_content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v0.9.8/Start-AzureEmulator.md
gitcommit: https://github.com/azure/azure-docs-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v0.9.8/Start-AzureEmulator.md
---

# Start-AzureEmulator
## SYNOPSIS
Starts the compute and storage emulators.

## SYNTAX

```
Start-AzureEmulator [-Launch] [-Mode]
```

## DESCRIPTION
This topic describes the cmdlet in the 0.8.10 version of the Microsoft Azure PowerShell module.
To get the version of the module you're using, in the Azure PowerShell console, type (Get-Module -Name Azure).Version.

The Start-AzureEmulator cmdlet starts both the compute and storage emulators and hosts the current service in the compute emulator.

## EXAMPLES

### 1: Start the emulator and launch a browser
```
PS C:\>Start-AzureEmulator -L
```

This example runs the service in the Azure emulator and launches a new browser window on the emulated service.

## PARAMETERS

### -Launch
Opens a new browser window on the service after hosting it in the emulator.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: ln

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -Mode
Specifies the emulator mode.
Valid values are: Full and Express.
The default value is Express.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 
Accepted values: Full, Express

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[New-AzureServiceProject](68b3e4a9-7aff-4274-bd8c-0f664cb6e65d)

[Publish-AzureServiceProject](4c0c0966-919e-49a6-9d38-c3c97355e281)

[Stop-AzureEmulator](91532648-9270-4b03-bd43-6fb7259a0df3)
