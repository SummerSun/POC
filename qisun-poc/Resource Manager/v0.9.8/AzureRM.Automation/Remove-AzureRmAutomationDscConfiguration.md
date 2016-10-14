---
external help file: RMAzure_Automation.xml
online version: 091cd841-4aaf-45de-a8f2-6f973fb9c91b
schema: 2.0.0
updated_at: 10/7/2016 9:35 AM
ms.date: 10/7/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/Resource%20Manager/v0.9.8/AzureRM.Automation/Remove-AzureRmAutomationDscConfiguration.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/3c5913303624ba7a7970d6758aac68ea04359cee/azureps-cmdlets-docs/Resource%20Manager/v0.9.8/AzureRM.Automation/Remove-AzureRmAutomationDscConfiguration.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: VSC CI Service
keywords: powershell, content
manager: Visual Studio China
---

# Remove-AzureRmAutomationDscConfiguration
## SYNOPSIS
Removes DSC configurations from Automation.

## SYNTAX

```
Remove-AzureRmAutomationDscConfiguration [-ResourceGroupName] <String> [-AutomationAccountName] <String>
 [-Name] <String> [-Force] [-Confirm] [-WhatIf]
```

## DESCRIPTION
The **Remove-AzureRmAutomationDscConfiguration** cmdlet removes APS Desired State Configuration (DSC) configurations from azure_2 Automation.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -AutomationAccountName
Specifies the name of the Automation account that contains DSC configurations that this cmdlet removes.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -Force
ps_force

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Specifies the name of the DSC configuration that this cmdlet removes.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ConfigurationName

Required: True
Position: 3
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of a resource group for which this cmdlet gets DSC configurations.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -Confirm
psdx_confirmdesc

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
psdx_whatifdesc

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Export-AzureRmAutomationDscConfiguration](091cd841-4aaf-45de-a8f2-6f973fb9c91b)

[Get-AzureRmAutomationDscConfiguration](cd411497-be17-46f7-8708-519f02312553)

[Import-AzureRmAutomationDscConfiguration](9e316628-0101-4da8-8a9f-843f8442e52d)

