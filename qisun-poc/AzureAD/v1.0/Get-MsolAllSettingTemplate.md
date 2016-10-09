---
external help file: AzureADHelpMSOL.xml
online version: 4a83b1b7-7b08-4983-9e41-bd873f8db2f8
schema: 2.0.0
updated_at: 2016-10-09T04:58:45.0000000Z
ms.date: 10/9/2016
ms.topic: reference
source_repo: https://github.com/SummerSun/azure-docs-powershell-azuread-int
source_branch: master
gitcommit: https://github.com/SummerSun/azure-docs-powershell-azuread-int/blob/7a791ca6c78fcafa80c91c7aac23301154805333/Azure%20AD%20Cmdlets/AzureAD/v1.0/Get-MsolAllSettingTemplate.md
---

# Get-MsolAllSettingTemplate

## SYNOPSIS
Gets all the directory setting templates that a tenant owns.

## SYNTAX

```
Get-MsolAllSettingTemplate
```

## DESCRIPTION
The **Get-MsolAllSettingTemplate** cmdlet gets all the directory setting templates that a tenant owns.

## EXAMPLES

### Example 1: Get a list of directory setting templates
```
PS C:\>Get-MsolAllSettingTemplate
```

This command gets a list of directory setting templates.

## PARAMETERS

## INPUTS

## OUTPUTS

### Microsoft.Online.Administration.SettingTemplate[]
This cmdlet returns a **SettingTemplate** object that has the following information: 

-- Id: The unique string ID of the directory setting template.
This value should be used when updating setting. 
-- DisplayName: The name of the setting template. 
-- Description: The description of the setting template. 
-- Values: The name value pair that describes setting template detail.

## NOTES

## RELATED LINKS

[Get-MsolSettingTemplate](4a83b1b7-7b08-4983-9e41-bd873f8db2f8)

[Get-MsolAllSettings](4955285a-6fe5-46e2-affc-8b1798ae8f2a)

[Get-MsolSettings](22a5d63b-5386-4137-965f-e5cf5696dde5)

