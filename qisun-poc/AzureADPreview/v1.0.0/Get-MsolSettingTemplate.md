---
external help file: Microsoft.Online.Administration.Automation.PSModule.dll-Help.xml
online version: 4955285a-6fe5-46e2-affc-8b1798ae8f2a
schema: 2.0.0
ms.assetid: 4A83B1B7-7B08-4983-9E41-BD873F8DB2F8
updated_at: 10/19/2016 3:31 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-azuread-int/blob/master/Azure%20AD%20Cmdlets/AzureADPreview/v1.0.0/Get-MsolSettingTemplate.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-azuread-int/blob/6a895a73e21f1df9572197497237f3a825ebd518/Azure%20AD%20Cmdlets/AzureADPreview/v1.0.0/Get-MsolSettingTemplate.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
ms.author: PowerShellHelpPub
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-MsolSettingTemplate

## SYNOPSIS
Gets a directory setting template.

## SYNTAX

```
Get-MsolSettingTemplate -TemplateId <String> [<CommonParameters>]
```

## DESCRIPTION
The **Get-MsolSettingTemplate** cmdlet gets a directory setting template.

## EXAMPLES

### Example 1: Get a directory setting template
```
PS C:\>Get-MsolSettingTemplate -TemplateId "566F7EA7-7BF1-4F4A-AF23-A1B46DBD46D6"
```

This command gets a directory setting template with the specified template ID.

## PARAMETERS

### -TemplateId
Specifies the template ID associated with the directory setting template that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Online.Administration.SettingTemplate
This cmdlet returns a directory setting template that contains the following information: 

- Id: The unique string ID of the directory setting template.
This value should be used when updating setting. 
- DisplayName: The name of the setting template. 
- Description: The description of the setting template. 
- Values: The name value pair that describes setting template detail.

## NOTES

## RELATED LINKS


