---
external help file: SMAzure_Compute.xml
online version: 
schema: 2.0.0
updated_at: 9/28/2016 10:35 AM
ms.date: 9/28/2016
ms.topic: reference
source_repo: https://github.com/SummerSun/poc-azure-powershell.git
source_branch: master
gitcommit: https://github.com/SummerSun/poc-azure-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v1.0/Remove-AzureStoreAddOn.md
---

# Remove-AzureStoreAddOn
## SYNOPSIS
Removes an existing add-on instance.

## SYNTAX

```
Remove-AzureStoreAddOn [-Name] <String> [-PassThru]
```

## DESCRIPTION
This topic describes the cmdlet in the 0.8.10 version of the Microsoft Azure PowerShell module.
To get the version of the module you're using, in the Azure PowerShell console, type (Get-Module -Name Azure).Version.

Removes an existing add-on instance from the current subscription.

## EXAMPLES

### Example 1
```
PS C:\>Remove-AzureStoreAddOn MyAddOn
```

This example removes an add-on named MyAddOn from the current subscription.

## PARAMETERS

### -Name
Specifies the name of the add-on instance to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PassThru
@{Text=}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureStoreAddOn](ceb557b5-e9af-4797-8385-94078de84662)

[New-AzureStoreAddOn](a293ef75-d822-4392-8af4-1bb50d0461f6)

[Set-AzureStoreAddOn](545b82f5-330f-48c7-b2b1-d6a1c630ac28)

