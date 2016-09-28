---
external help file: RMAzure_Automation.xml
online version: 0cfa1dd4-11f2-4eb6-a354-46bf4286d00f
schema: 2.0.0
updated_at: 9/8/2016 10:40 AM
ms.date: 9/8/2016
ms.topic: reference
content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Resource%20Manager/Automation%20Cmdlets/v0.9.8/Get-AzureRmAutomationModule.md
original_content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Resource%20Manager/Automation%20Cmdlets/v0.9.8/Get-AzureRmAutomationModule.md
gitcommit: https://github.com/azure/azure-docs-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Resource%20Manager/Automation%20Cmdlets/v0.9.8/Get-AzureRmAutomationModule.md
---

# Get-AzureRmAutomationModule
## SYNOPSIS
Gets metadata for modules from Automation.

## SYNTAX

### UNNAMED_PARAMETER_SET_1
```
Get-AzureRmAutomationModule [-ResourceGroupName] <String> [-AutomationAccountName] <String>
```

### UNNAMED_PARAMETER_SET_2
```
Get-AzureRmAutomationModule [-ResourceGroupName] <String> [-AutomationAccountName] <String> [-Name] <String>
```

## DESCRIPTION
The **Get-AzureRmAutomationModule** cmdlet gets metadata for modules from azure_2 Automation.

## EXAMPLES

### Example 1: Get all modules
```
PS C:\>Get-AzureRmAutomationModule -AutomationAccountName "Contoso17" -ResourceGroupName "ResourceGroup01"
```

This command gets all modules in the Automation account named Contoso17.

### Example 2: Get a module
```
PS C:\>Get-AzureRmAutomationModule -AutomationAccountName "Contoso17" -Name "ContosoModule" -ResourceGroupName "ResourceGroup01"
```

This command gets a module named ContosoModule in the Automation account named Contoso17.

## PARAMETERS

### -AutomationAccountName
Specifies the name of the Automation account for which this cmdlet gets module metadata.

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

### -Name
Specifies the name of the module for which this cmdlet gets metadata.

```yaml
Type: String
Parameter Sets: UNNAMED_PARAMETER_SET_2
Aliases: 

Required: True
Position: 3
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of a resource group for which this cmdlet gets module metadata.

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

## NOTES

## RELATED LINKS

[New-AzureRmAutomationModule](0cfa1dd4-11f2-4eb6-a354-46bf4286d00f)

[Remove-AzureRmAutomationModule](762b2b43-579b-4869-98f9-882aaf224686)

[Set-AzureRmAutomationModule](e47306c4-b17e-4651-8248-eb81ad448a17)
