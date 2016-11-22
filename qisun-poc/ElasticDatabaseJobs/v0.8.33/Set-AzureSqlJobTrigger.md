---
external help file: Microsoft.Azure.SqlDatabase.Jobs.PowerShell.dll-Help.xml
online version:
schema: 2.0.0
ms.assetid: EB20D3D1-44CB-4E92-A9B9-D15AFAECBA73
updated_at: 11/17/2016 5:33 AM
ms.date: 11/17/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ElasticDatabaseJobs/v0.8.33/Set-AzureSqlJobTrigger.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/2692a7998846b66d06a416c56978167da402f8d5/azureps-cmdlets-docs/ElasticDatabaseJobs/v0.8.33/Set-AzureSqlJobTrigger.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
ms.author: PowerShellHelpPub
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Set-AzureSqlJobTrigger

## SYNOPSIS
Sets a job trigger.

## SYNTAX

```
Set-AzureSqlJobTrigger -JobName <String> -ScheduleName <String> -Enabled <Boolean>
 [[-AzureSqlJobConnection] <AzureSqlJobConnection>] [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureSqlJobTrigger** cmdlet sets a job trigger.

## EXAMPLES

### Example 1: Disable job executions from the job trigger
```
PS C:\>Set-AzureSqlDatabaseJobTrigger -JobName "MyJob" -ScheduleName "MySchedule" -Enabled $False
```

This command disables further job executions from the job trigger that binds the job named MyJob and the schedule named MySchedule.

## PARAMETERS

### -AzureSqlJobConnection
Specifies the connection state object for the job.
You can get the connection state object through the [New-AzureSqlJobConnection](./New-AzureSqlJobConnection.md) cmdlet.
If you do not specify this parameter, the connection state is used from a prior call to the [Use-AzureSqlJobConnection](./Use-AzureSqlJobConnection.md) cmdlet.

```yaml
Type: AzureSqlJobConnection
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Enabled
Indicates whether the trigger is enabled.

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -JobName
Specifies the name of the job.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ScheduleName
Specifies the name of the schedule.

```yaml
Type: String
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

[Get-AzureSqlJobTrigger](xref:ElasticDatabaseJobs/v0.8.33/Get-AzureSqlJobTrigger.md)

[New-AzureSqlJobTrigger](xref:ElasticDatabaseJobs/v0.8.33/New-AzureSqlJobTrigger.md)

[Remove-AzureSqlJobTrigger](xref:ElasticDatabaseJobs/v0.8.33/Remove-AzureSqlJobTrigger.md)

[Azure Elastic Database Jobs Cmdlets](xref:ElasticDatabaseJobs/v0.8.33/ElasticDatabaseJobs.md)
