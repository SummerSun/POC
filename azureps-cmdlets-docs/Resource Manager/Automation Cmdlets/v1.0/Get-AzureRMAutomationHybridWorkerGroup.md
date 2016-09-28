---
external help file: RMAzure_Automation.xml
online version: a6f623a1-2e69-4ea2-828b-ab63d285a009
schema: 2.0.0
updated_at: 9/8/2016 10:40 AM
ms.date: 9/8/2016
ms.topic: reference
content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Resource%20Manager/Automation%20Cmdlets/v1.0/Get-AzureRMAutomationHybridWorkerGroup.md
original_content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Resource%20Manager/Automation%20Cmdlets/v1.0/Get-AzureRMAutomationHybridWorkerGroup.md
gitcommit: https://github.com/azure/azure-docs-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Resource%20Manager/Automation%20Cmdlets/v1.0/Get-AzureRMAutomationHybridWorkerGroup.md
---

# Get-AzureRMAutomationHybridWorkerGroup
## SYNOPSIS
Gets hybrid runbook worker groups.

## SYNTAX

### UNNAMED_PARAMETER_SET_1
```
Get-AzureRMAutomationHybridWorkerGroup [-ResourceGroupName] <String> [-AutomationAccountName] <String>
```

### UNNAMED_PARAMETER_SET_2
```
Get-AzureRMAutomationHybridWorkerGroup [-ResourceGroupName] <String> [-AutomationAccountName] <String>
 [[-Name] <String>]
```

## DESCRIPTION
The **Get-AzureRmAutomationHybridWorkerGroup** cmdlet gets azure_2 Automation hybrid runbook worker groups.
To get a specific group, specify its name.

## EXAMPLES

### Example 1: Get all hybrid runbook worker groups
```
PS C:\>Get-AzureRMAutomationHybridWorkerGroup -ResourceGroupName "ResourceGroupName01" -AutomationAccountName "Contoso17"
```

This command gets all hybrid runbook worker groups in the Automation account named Contoso17.

### Example 2: Get a single hybrid runbook worker group
```
PS C:\>Get-AzureRMAutomationHybridWorkerGroup -ResourceGroupName "ResourceGroupName01" -AutomationAccountName "Contoso17" -Name "HybridRunbookWorkerGroup01"
```

This command gets the hybrid runbook worker group named HybridRunbookWorkerGroup01 in the Automation account named Contoso17.

### Example 3: Get the workers in a hybrid runbook worker group
```
PS C:\>(Get-AzureRMAutomationHybridWorker -ResourceGroupName ResourceGroupName01 -AutomationAccountName Contoso17 -Name "HybridRunbookWorkerGroup01" ).RunbookWorker
```

This command gets the hybrid runbook workers in the hybrid runbook worker group named HybridRunbookWorkerGroup01 in the Automation account named Contoso17.

## PARAMETERS

### -AutomationAccountName
Specifies the name of an Automation account.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the hybrid runbook worker group name.

```yaml
Type: String
Parameter Sets: UNNAMED_PARAMETER_SET_2
Aliases: Group

Required: False
Position: 3
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group.

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

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.Automation.Model.HybridRunbookWorker

## NOTES

## RELATED LINKS
