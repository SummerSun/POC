---
external help file: Microsoft.Azure.Commands.Scheduler.dll-Help.xml
online version: .\Disable-AzureRmSchedulerJobCollection.md
schema: 2.0.0
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Scheduler/v0.10.0/Get-AzureRmSchedulerJobCollection.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Scheduler/v0.10.0/Get-AzureRmSchedulerJobCollection.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmSchedulerJobCollection

## SYNOPSIS
Gets job collections.

## SYNTAX

```
Get-AzureRmSchedulerJobCollection [-ResourceGroupName <String>] [-JobCollectionName <String>]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSchedulerJobCollection** cmdlet gets job collections in Azure Scheduler.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ResourceGroupName
Specifies resource group from which this cmdlet gets job collections.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -JobCollectionName
Specifies the name of a job collection.

```yaml
Type: String
Parameter Sets: (All)
Aliases: Name, ResourceName

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

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

## NOTES

## RELATED LINKS

[Disable-AzureRmSchedulerJobCollection](.\Disable-AzureRmSchedulerJobCollection.md)

[Enable-AzureRmSchedulerJobCollection](.\Enable-AzureRmSchedulerJobCollection.md)

[New-AzureRmSchedulerJobCollection](.\New-AzureRmSchedulerJobCollection.md)

[Remove-AzureRmSchedulerJobCollection](.\Remove-AzureRmSchedulerJobCollection.md)

[Set-AzureRmSchedulerJobCollection](.\Set-AzureRmSchedulerJobCollection.md)

