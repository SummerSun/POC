---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: .\Remove-AzureVMChefExtension.md
schema: 2.0.0
ms.assetid: A607EBCA-104F-4B40-AE56-7339AD63EA2E
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/Get-AzureVMChefExtension.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/Get-AzureVMChefExtension.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureVMChefExtension

## SYNOPSIS
Gets the Chef extension applied on a virtual machine.

## SYNTAX

```
Get-AzureVMChefExtension -VM <IPersistentVM> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVMChefExtension** cmdlet gets the Chef extension applied on a virtual machine.

## EXAMPLES

### Example 1: Get the Chef extension applied on the specified virtual machine
```
PS C:\>Get-AzureVMChefExtension -VM $VM;
```

This command gets the Chef extension applied on the specified virtual machine.

## PARAMETERS

### -VM
Specifies the persistent virtual machine object.

```yaml
Type: IPersistentVM
Parameter Sets: (All)
Aliases: InputObject

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
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

[Remove-AzureVMChefExtension](.\Remove-AzureVMChefExtension.md)

[Set-AzureVMChefExtension](.\Set-AzureVMChefExtension.md)

[Azure Service Cmdlets](.\Azure.Service.md)


