---
external help file: SMAzure_Compute.xml
online version: 
schema: 2.0.0
updated_at: 10/7/2016 9:35 AM
ms.date: 10/7/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/Service%20Management/v1.0/Compute/Save-AzureServiceProjectPackage.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/3c5913303624ba7a7970d6758aac68ea04359cee/azureps-cmdlets-docs/Service%20Management/v1.0/Compute/Save-AzureServiceProjectPackage.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: VSC CI Service
keywords: powershell, content
manager: Visual Studio China
---

# Save-AzureServiceProjectPackage
## SYNOPSIS
Packages the service project into Azure cloud package (*.cspkg).

## SYNTAX

```
Save-AzureServiceProjectPackage [-Local]
```

## DESCRIPTION
This topic describes the cmdlet in the 0.8.10 version of the Microsoft Azure PowerShell module.
To get the version of the module you're using, in the Azure PowerShell console, type (Get-Module -Name Azure).Version.

The Save-AzureServiceProjectPackage cmdlet packages the service project into an Azure cloud package (*.cspkg).

## EXAMPLES

### 1: Create a service project package
```
PS C:\>Save-AzureServiceProjectPackage
```

This example creates a *.cspgk for a service project named MyAzureServiceProject.

## PARAMETERS

### -Local
@{Text=}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: l

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Publish-AzureServiceProject](4c0c0966-919e-49a6-9d38-c3c97355e281)

