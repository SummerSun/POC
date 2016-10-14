---
external help file: AzureADHelpMSOL.xml
online version: 22a5d63b-5386-4137-965f-e5cf5696dde5
schema: 2.0.0
updated_at: 9/28/2016 9:53 AM
ms.date: 9/28/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-azuread-int/blob/master/Azure%20AD%20Cmdlets/AzureAD/v1.0/Get-MsolAllSettings.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-azuread-int/blob/aa68880375be962d5646d6d763347021b391b5c6/Azure%20AD%20Cmdlets/AzureAD/v1.0/Get-MsolAllSettings.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: VSC CI Service
keywords: powershell, content
manager: Visual Studio China
---

# Get-MsolAllSettings

## SYNOPSIS
Gets all directory settings object associated with tenant or group/user/service principal/application/device.

## SYNTAX

```
Get-MsolAllSettings [-TargetObjectId <String>] [-TargetType]
```

## DESCRIPTION
The **Get-MsolAllSettings** cmdlet gets all directory settings object associated with tenant or group/user/service principal/application/device.

## EXAMPLES

### Example 1: Get a list of directory settings
```
PS C:\>Get-MsolAllSettings
```

This command gets a list of directory settings

### Example 2:
```
PS C:\>Get-MsolAllSettings -TargetType Groups -TargetObjectId "Group001"
```

This command gets a list of directory settings associated with groups target type that belong to the target object ID named Group001.

## PARAMETERS

### -TargetObjectId
Specifies the object ID that setting objects are associated with, if this value is not specified, the cmdlet associates with tenant.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True(ByValue,ByPropertyName)
Accept wildcard characters: False
```

### -TargetType
Specifies the object type that settings objects are associated with, if this value is not specified, this cmdlet associates with tenant.

The acceptable values for this parameter are:

-- Groups
-- Users
-- ServicePrincipals
-- Applications
-- Devices

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 
Accepted values: Groups, Users, ServicePrincipals, Applications, Devices

Required: False
Position: Named
Default value: None
Accept pipeline input: True(ByValue,ByPropertyName)
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-MsolSettings](22a5d63b-5386-4137-965f-e5cf5696dde5)

[Get-MsolAllSettingTemplate](0f14f9f7-1780-4cb2-9362-415a361463be)

