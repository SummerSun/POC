---
external help file: RMAzure_Automation.xml
online version: 73a4a9ba-477c-41e6-9193-2be97182e07d
schema: 2.0.0
updated_at: 9/28/2016 10:35 AM
ms.date: 9/28/2016
ms.topic: reference
source_repo: https://github.com/SummerSun/poc-azure-powershell.git
source_branch: master
gitcommit: https://github.com/SummerSun/poc-azure-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Resource%20Manager/Automation%20Cmdlets/v1.0/Set-AzureRMAutomationSchedule.md
---

# Set-AzureRMAutomationSchedule
## SYNOPSIS
Modifies an Automation schedule.

## SYNTAX

```
Set-AzureRMAutomationSchedule [-ResourceGroupName] <String> [-AutomationAccountName] <String> [-Name] <String>
 [-Description <String>] [-IsEnabled <Boolean]>]
```

## DESCRIPTION
The **Set-AzureRmAutomationSchedule** cmdlet modifies a schedule in azure_2 Automation.

## EXAMPLES

### Example 1: Modify a schedule
```
PS C:\>Set-AzureRmAutomationSchedule -AutomationAccountName "Contoso17" -Name "Schedule01" -Description "Automation Schedule" -ResourceGroupName "ResourceGroup01"
```

This command modifies the description of the schedule named Schedule01.

## PARAMETERS

### -AutomationAccountName
Specifies the name of an Automation account for which this cmdlet modifies a schedule.

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

### -Description
Specifies a description for the schedule.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -IsEnabled
Specifies whether this cmdlet enables the schedule.

```yaml
Type: Boolean]
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name for the schedule that this cmdlet modifies.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 3
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of a resource group for which this cmdlet modifies a schedule.

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

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.Automation.Model.Schedule

## NOTES

## RELATED LINKS

[Get-AzureRmAutomationSchedule](73a4a9ba-477c-41e6-9193-2be97182e07d)

[New-AzureRmAutomationSchedule](36c11dd3-5843-49d2-8baa-9f5aa737d345)

[Remove-AzureRmAutomationSchedule](633c3e61-0da0-4a01-897b-e81c6e571196)

