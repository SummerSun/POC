---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: .\Get-AzureRmSiteRecoveryStorageClassificationMapping.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.0/CmdletMDs/New-AzureRmSiteRecoveryStorageClassificationMapping.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.0/CmdletMDs/New-AzureRmSiteRecoveryStorageClassificationMapping.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmSiteRecoveryStorageClassificationMapping

## SYNOPSIS
Creates a storage classification mapping in Site Recovery.

## SYNTAX

```
New-AzureRmSiteRecoveryStorageClassificationMapping -PrimaryStorageClassification <ASRStorageClassification>
 -RecoveryStorageClassification <ASRStorageClassification> [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmSiteRecoveryStorageClassificationMapping** cmdlet creates a storage classification mapping in Azure Site Recovery.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -PrimaryStorageClassification
Specifies the primary storage classification mapping.

```yaml
Type: ASRStorageClassification
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -RecoveryStorageClassification
Specifies a recovery storage classification mapping.

```yaml
Type: ASRStorageClassification
Parameter Sets: (All)
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

[Get-AzureRmSiteRecoveryStorageClassificationMapping](.\Get-AzureRmSiteRecoveryStorageClassificationMapping.md)

[Remove-AzureRmSiteRecoveryStorageClassificationMapping](.\Remove-AzureRmSiteRecoveryStorageClassificationMapping.md)

