---
external help file: Microsoft.Azure.Commands.Insights.dll-Help.xml
online version: .\Add-AzureRmAutoscaleSetting.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Insights/v2.0/CmdletMDs/Remove-AzureRmAutoscaleSetting.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.Insights/v2.0/CmdletMDs/Remove-AzureRmAutoscaleSetting.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Remove-AzureRmAutoscaleSetting

## SYNOPSIS
Removes an Autoscale setting.

## SYNTAX

```
Remove-AzureRmAutoscaleSetting -ResourceGroup <String> -Name <String> [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmAutoscaleSetting** cmdlet removes an Autoscale setting.
You must specify the name of the setting and the name of the resource group to which it is assigned.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ResourceGroup
Specifies the name of the resource group.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name of the Autoscale setting to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Add-AzureRmAutoscaleSetting](.\Add-AzureRmAutoscaleSetting.md)

[Get-AzureRmAutoscaleSetting](.\Get-AzureRmAutoscaleSetting.md)

