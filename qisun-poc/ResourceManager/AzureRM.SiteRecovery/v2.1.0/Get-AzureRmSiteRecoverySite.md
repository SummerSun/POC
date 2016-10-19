---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: .\New-AzureRmSiteRecoverySite.md
schema: 2.0.0
ms.assetid: 00FF760F-D831-4061-8CC3-7B3A7F376A35
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.1.0/Get-AzureRmSiteRecoverySite.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.1.0/Get-AzureRmSiteRecoverySite.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmSiteRecoverySite

## SYNOPSIS
Gets the Hyper-V sites from the Site Recovery vault.

## SYNTAX

### Default (Default)
```
Get-AzureRmSiteRecoverySite [<CommonParameters>]
```

### ByName
```
Get-AzureRmSiteRecoverySite -Name <String> [<CommonParameters>]
```

### ByFriendlyName
```
Get-AzureRmSiteRecoverySite -FriendlyName <String> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSiteRecoverySite** cmdlet gets the Hyper-V sites in the Azure Site Recovery vault.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -FriendlyName
Specifies the friendly name of the site.

```yaml
Type: String
Parameter Sets: ByFriendlyName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Specifies the name of the site.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
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

[New-AzureRmSiteRecoverySite](.\New-AzureRmSiteRecoverySite.md)

[Remove-AzureRmSiteRecoverySite](.\Remove-AzureRmSiteRecoverySite.md)


