---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: .\Get-AzureRmSiteRecoveryVaultSettings.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.0/CmdletMDs/Set-AzureRmSiteRecoveryVaultSettings.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.0/CmdletMDs/Set-AzureRmSiteRecoveryVaultSettings.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Set-AzureRmSiteRecoveryVaultSettings

## SYNOPSIS
Set the Site Recovery vault context for further operations.

## SYNTAX

### AzureSiteRecoveryVault
```
Set-AzureRmSiteRecoveryVaultSettings -ASRVault <ASRVault> [<CommonParameters>]
```

### AzureRecoveryServicesVault
```
Set-AzureRmSiteRecoveryVaultSettings -ARSVault <ARSVault> [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureRmSiteRecoveryVaultSettings** cmdlet sets the Azure Site Recovery vault context for further operations.
This does not apply to recovery services vaults.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ARSVault
Specifies an **ARSVault** object.

```yaml
Type: ARSVault
Parameter Sets: AzureRecoveryServicesVault
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ASRVault
Specifies an **ASRVault** object.

```yaml
Type: ASRVault
Parameter Sets: AzureSiteRecoveryVault
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmSiteRecoveryVaultSettings](.\Get-AzureRmSiteRecoveryVaultSettings.md)

