---
external help file: SMAzure_Compute.xml
online version: 
schema: 2.0.0
updated_at: 10/7/2016 9:35 AM
ms.date: 10/7/2016
ms.topic: reference
source_repo: https://github.com/SummerSun/azure-docs-powershell-int
source_branch: master
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/3c5913303624ba7a7970d6758aac68ea04359cee/azureps-cmdlets-docs/Service%20Management/v0.9.8/Azure.Compute/Add-AzurePHPWebRole.md
---

# Add-AzurePHPWebRole
## SYNOPSIS
Creates the required files and configuration (sometimes referred to as scaffolding) for a PHP application.

## SYNTAX

```
Add-AzurePHPWebRole [[-Name] <String>] [[-Instances] <Int32>]
```

## DESCRIPTION
This topic describes the cmdlet in the 0.8.10 version of the Microsoft Azure PowerShell module.
To get the version of the module you're using, in the Azure PowerShell console, type (Get-Module -Name Azure).Version.

The Add-AzurePHPWebRole cmdlet creates the files and configuration (sometimes referred to as scaffolding) for a PHP application that will be hosted in Azure through IIS.

## EXAMPLES

### 1: Add a web role using default values
```
PS C:\>Add-AzurePHPWebRole
```

This example adds the required files and configuration for new web role using the default values of a service named "WebRole1" with 1 instance.

### 2: Add a web role with multiple instances
```
PS C:\>Add-AzurePHPWebRole MyWebRole -I 2
```

This example adds the required files and configuration for a new web role to the current application, using the name "MyWebRole" and a role instance count of 2.

## PARAMETERS

### -Instances
Specifies the number of role instances for this web role.
The default is 1.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: i

Required: False
Position: 2
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Specifies the name of the web role.
The name determines the name of the directory that contains the required files and configuration for the PHP application.
The default is WebRole#, where # is the number of web roles in the service.

```yaml
Type: String
Parameter Sets: (All)
Aliases: n

Required: False
Position: 1
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Add-AzurePHPWorkerRole](4759ce95-bb7a-46f0-8125-2a1966f572d4)

[New-AzureServiceProject](68b3e4a9-7aff-4274-bd8c-0f664cb6e65d)

