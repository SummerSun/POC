---
external help file: Microsoft.Azure.Commands.Batch.dll-Help.xml
online version: .\Disable-AzureBatchJobSchedule.md
schema: 2.0.0
ms.assetid: B1566014-74E1-4EA9-985F-6CEB3B2EDF04
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v1.1.4/Stop-AzureBatchJobSchedule.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v1.1.4/Stop-AzureBatchJobSchedule.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Stop-AzureBatchJobSchedule

## SYNOPSIS
Stops a Batch job schedule.

## SYNTAX

```
Stop-AzureBatchJobSchedule [-Id] <String> -BatchContext <BatchAccountContext> [<CommonParameters>]
```

## DESCRIPTION
The **Stop-AzureBatchJobSchedule** cmdlet stops an azure_2 Batch job schedule.

## EXAMPLES

### Example 1: Stop a job schedule
```
PS C:\>Stop-AzureBatchJobSchedule -Id "JobSchedule17" -BatchContext $Context
```

This command stops the job schedule that has the ID JobSchedule17.
Use the Get-AzureRmBatchAccountKeys cmdlet to assign a context to the $Context variable.

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

### -Id
Specifies the ID of the job schedule that this cmdlet stops.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Disable-AzureBatchJobSchedule](.\Disable-AzureBatchJobSchedule.md)

[Enable-AzureBatchJobSchedule](.\Enable-AzureBatchJobSchedule.md)

[Get-AzureRmBatchAccountKeys](.\Get-AzureRmBatchAccountKeys.md)

[Get-AzureBatchJobSchedule](.\Get-AzureBatchJobSchedule.md)

[New-AzureBatchJobSchedule](.\New-AzureBatchJobSchedule.md)

[Remove-AzureBatchJobSchedule](.\Remove-AzureBatchJobSchedule.md)

[Azure Batch Cmdlets](.\AzureRM.Batch.md)


