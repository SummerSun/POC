---
external help file: Microsoft.Azure.Commands.Automation.dll-Help.xml
online version: http://go.microsoft.com/fwlink/?LinkId=397907
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v2.0/CmdletMDs/Get-AzureAutomationSchedule.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v2.0/CmdletMDs/Get-AzureAutomationSchedule.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureAutomationSchedule

## SYNOPSIS
Gets an Azure Automation schedule.

## SYNTAX

### ByAll (Default)
```
Get-AzureAutomationSchedule [-AutomationAccountName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

### ByName
```
Get-AzureAutomationSchedule [-Name] <String> [-AutomationAccountName] <String> [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureAutomationSchedule** cmdlet gets a Microsoft Azure Automation schedule.

## EXAMPLES

### Example 1: Get a schedule
```
PS C:\> Get-AzureAutomationSchedule -AutomationAccountName "Contoso17" -Name "DailySchedule08"
```

This command gets the schedule named DailySchedule08.

## PARAMETERS

### -AutomationAccountName
Specifies the name of an Azure Automation account.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name of a schedule.

```yaml
Type: String
Parameter Sets: ByName
Aliases: ScheduleName

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
@{Text=}

```yaml
Type: AzureSMProfile
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

### Microsoft.Azure.Commands.Automation.Model.Schedule

## NOTES

## RELATED LINKS

[New-AzureAutomationSchedule](.\New-AzureAutomationSchedule.md)

[Remove-AzureAutomationSchedule](.\Remove-AzureAutomationSchedule.md)

[Set-AzureAutomationSchedule](.\Set-AzureAutomationSchedule.md)

