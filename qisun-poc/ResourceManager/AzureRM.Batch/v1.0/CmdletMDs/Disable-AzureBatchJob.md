---
external help file: Microsoft.Azure.Commands.Batch.dll-Help.xml
online version: .\Enable-AzureBatchJob.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v1.0/CmdletMDs/Disable-AzureBatchJob.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v1.0/CmdletMDs/Disable-AzureBatchJob.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Disable-AzureBatchJob

## SYNOPSIS
Disables a Batch job.

## SYNTAX

```
Disable-AzureBatchJob [-Id] <String> [-DisableJobOption] <DisableJobOption> -BatchContext <BatchAccountContext>
 [<CommonParameters>]
```

## DESCRIPTION
The **Disable-AzureBatchJob** cmdlet disables an azure_2 Batch job.
After you enable a job, new tasks can run.
Disabled jobs do not run new tasks.
You can enable a disabled job later.

## EXAMPLES

### Example 1: Disable a Batch job
```
PS C:\>Disable-AzureBatchJob -Id "Job-000001" -DisableJobOption "Terminate" -BatchContext $Context
```

This command disables the job that has the ID Job-000001.
The command terminates active tasks for the job.
Use the **Get-AzureRmBatchAccountKeys** cmdlet to assign a context to the $Context variable.

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

### -DisableJobOption
Specifies what to do with active tasks associated with the job that this cmdlet disables.
Valid values are: 

- Requeue 
- Terminate 
- Wait

```yaml
Type: DisableJobOption
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Specifies the ID of the job that this cmdlet disables.

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

[Enable-AzureBatchJob](.\Enable-AzureBatchJob.md)

[Get-AzureRmBatchAccountKeys](.\Get-AzureRmBatchAccountKeys.md)

[Get-AzureBatchJob](.\Get-AzureBatchJob.md)

[New-AzureBatchJob](.\New-AzureBatchJob.md)

[Remove-AzureBatchJob](.\Remove-AzureBatchJob.md)

[Stop-AzureBatchJob](.\Stop-AzureBatchJob.md)

[Azure Batch Cmdlets](.\AzureRM.Batch.md)

