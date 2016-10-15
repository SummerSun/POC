---
external help file: Microsoft.Azure.Commands.Batch.dll-Help.xml
online version: .\Disable-AzureBatchJobSchedule.md
schema: 2.0.0
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/projects/azure-docs-powershell-int/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v1.0/CmdletMDs/Get-AzureBatchJobSchedule.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/projects/azure-docs-powershell-int/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v1.0/CmdletMDs/Get-AzureBatchJobSchedule.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Get-AzureBatchJobSchedule

## SYNOPSIS
Gets Batch job schedules.

## SYNTAX

### ODataFilter (Default)
```
Get-AzureBatchJobSchedule [-Filter <String>] [-MaxCount <Int32>] [-Select <String>] [-Expand <String>]
 -BatchContext <BatchAccountContext> [<CommonParameters>]
```

### Id
```
Get-AzureBatchJobSchedule [[-Id] <String>] [-Select <String>] [-Expand <String>]
 -BatchContext <BatchAccountContext> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureBatchJobSchedule** cmdlet gets azure_2 Batch job schedules for the Batch account specified by the *BatchContext* parameter.
Specify an ID to get a single job schedule.
Specify the *Filter* parameter to get the job schedules that match an Open Data Protocol (OData) filter.

## EXAMPLES

### Example 1: Get a job schedule by specifying an ID
```
PS C:\>Get-AzureBatchJobSchedule -Id "JobSchedule23" -BatchContext $Context
CreationTime                : 7/25/2015 9:15:43 PM
DisplayName                 : 
ETag                        : 0x8D2953633427FCA
ExecutionInformation        : Microsoft.Azure.Commands.Batch.Models.PSJobScheduleExecutionInformation
Id                          : JobSchedule23
JobSpecification            : Microsoft.Azure.Commands.Batch.Models.PSJobSpecification
LastModified                : 7/25/2015 9:15:43 PM
Metadata                    : 
PreviousState               : Invalid
PreviousStateTransitionTime : 
Schedule                    : 
State                       : Active
StateTransitionTime         : 7/25/2015 9:15:43 PM
Statistics                  : 
Url                         : https://pfuller.westus.batch.azure.com/jobschedules/JobSchedule23
```

This command gets the job schedule that has the ID JobSchedule23.
Use the Get-AzureRmBatchAccountKeys cmdlet to assign a context to the $Context variable.

### Example 2: Get job schedules by using a filter
```
PS C:\>Get-AzureBatchJobSchedule -Filter "startswith(id,'Job')" -BatchContext $Context
CreationTime                : 7/25/2015 9:15:43 PM
DisplayName                 : 
ETag                        : 0x8D2953633427FCA
ExecutionInformation        : Microsoft.Azure.Commands.Batch.Models.PSJobScheduleExecutionInformation
Id                          : JobSchedule23
JobSpecification            : Microsoft.Azure.Commands.Batch.Models.PSJobSpecification
LastModified                : 7/25/2015 9:15:43 PM
Metadata                    : 
PreviousState               : Invalid
PreviousStateTransitionTime : 
Schedule                    : 
State                       : Active
StateTransitionTime         : 7/25/2015 9:15:43 PM
Statistics                  : 
Url                         : https://pfuller.westus.batch.azure.com/jobschedules/JobSchedule23

CreationTime                : 7/26/2015 5:39:33 PM
DisplayName                 : 
ETag                        : 0x8D295E12B1084B4
ExecutionInformation        : Microsoft.Azure.Commands.Batch.Models.PSJobScheduleExecutionInformation
Id                          : JobSchedule26
JobSpecification            : Microsoft.Azure.Commands.Batch.Models.PSJobSpecification
LastModified                : 7/26/2015 5:39:33 PM
Metadata                    : 
PreviousState               : Invalid
PreviousStateTransitionTime : 
Schedule                    : 
State                       : Active
StateTransitionTime         : 7/26/2015 5:39:33 PM
Statistics                  : 
Url                         : https://pfuller.westus.batch.azure.com/jobschedules/JobSchedule26
```

This command gets all job schedules that have IDs that start with Job by specifying the *Filter* parameter.

## PARAMETERS

### -BatchContext
Specifies the **BatchAccountContext** instance that this cmdlet uses to interact with the Batch service.
To obtain a **BatchAccountContext** object that contains access keys for your subscription, use the Get-AzureRmBatchAccountKeys cmdlet.

```yaml
Type: BatchAccountContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Expand
Specifies an Open Data Protocol (OData) expand clause.
Specify a value for this parameter to get associated entities of the main entity that you get.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Filter
Specifies an OData filter clause.
This cmdlet returns job schedules that match the filter that this parameter specifies.
If you do not specify a filter, this cmdlet returns all job schedules for the Batch context.

```yaml
Type: String
Parameter Sets: ODataFilter
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Specifies the ID of the job schedule that this cmdlet gets.
You cannot specify wildcard characters.

```yaml
Type: String
Parameter Sets: Id
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -MaxCount
Specifies the maximum number of job schedules to return.
If you specify a value of zero (0) or less, the cmdlet does not use an upper limit.
The default value is 1000.

```yaml
Type: Int32
Parameter Sets: ODataFilter
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Select
Specifies an OData select clause.
Specify a value for this parameter to get specific properties rather than all object properties.

```yaml
Type: String
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

### PSCloudJobSchedule

## NOTES

## RELATED LINKS

[Disable-AzureBatchJobSchedule](.\Disable-AzureBatchJobSchedule.md)

[Enable-AzureBatchJobSchedule](.\Enable-AzureBatchJobSchedule.md)

[Get-AzureRmBatchAccountKeys](.\Get-AzureRmBatchAccountKeys.md)

[New-AzureBatchJobSchedule](.\New-AzureBatchJobSchedule.md)

[Remove-AzureBatchJobSchedule](.\Remove-AzureBatchJobSchedule.md)

[Stop-AzureBatchJobSchedule](.\Stop-AzureBatchJobSchedule.md)

[Azure Batch Cmdlets](.\AzureRM.Batch.md)
