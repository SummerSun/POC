---
external help file: Microsoft.Azure.Commands.Insights.dll-Help.xml
online version: .\Add-AzureRmLogAlertRule.md
schema: 2.0.0
ms.assetid: 2AF0D56E-542D-48DC-AF5D-B8752E0C343A
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Insights/v1.0.12/New-AzureRmAlertRuleWebhook.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Insights/v1.0.12/New-AzureRmAlertRuleWebhook.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmAlertRuleWebhook

## SYNOPSIS
Creates an alert rule webhook.

## SYNTAX

```
New-AzureRmAlertRuleWebhook [-ServiceUri] <String> [[-Properties] <Hashtable>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmAlertRuleWebhook** cmdlet creates an alert rule webhook.

## EXAMPLES

### Example 1: Create an alert rule webhook
```
PS C:\>New-AzureRmAlertRuleWebhook -ServiceUri "http://contoso.com"
```

This command creates an alert rule webhook by specifying only the service URI.

### Example 2: Create a webhook with one property
```
PS C:\>$Actual = New-AzureRmAlertRuleWebhook -ServiceUri "http://contoso.com" -Properties @{prop1 = 'value1'}
```

This command creates an alert rule webhook for Contoso.com that has one property, and then stores it in the $Actual variable.

## PARAMETERS

### -ServiceUri
Specifies the service URI.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Properties
Specifies the list of properties in the format @(property1 = 'value1',....).

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
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

[Add-AzureRmLogAlertRule](.\Add-AzureRmLogAlertRule.md)

[Add-AzureRmMetricAlertRule](.\Add-AzureRmMetricAlertRule.md)

[Add-AzureRmWebtestAlertRule](.\Add-AzureRmWebtestAlertRule.md)

[New-AzureRmAlertRuleEmail](.\New-AzureRmAlertRuleEmail.md)

[New-AzureRmAutoscaleWebhook](.\New-AzureRmAutoscaleWebhook.md)


