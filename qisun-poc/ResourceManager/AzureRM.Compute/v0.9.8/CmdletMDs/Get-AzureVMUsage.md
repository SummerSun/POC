---
external help file: Microsoft.Azure.Commands.Compute.dll-Help.xml
online version: b745860c-13a7-4ebc-aafd-9e5efa9832de
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v0.9.8/CmdletMDs/Get-AzureVMUsage.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v0.9.8/CmdletMDs/Get-AzureVMUsage.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Get-AzureVMUsage

## SYNOPSIS
Gets the virtual machine core count usage for a location.

## SYNTAX

```
Get-AzureVMUsage [-Location] <String> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVMUsage** cmdlet gets the virtual machine core count usage for a location.

## EXAMPLES

### Example 1: Get core count usage for a location
```
PS C:\>Get-AzureVMUsage -Location "Central US"
```

This command gets the virtual machine core count usage for the location Central US.

## PARAMETERS

### -Location
Specifies the location for which this cmdlet gets virtual machine core count usage.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

