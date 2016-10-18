---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: 
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/Get-AzureStoreAddOn.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/Get-AzureStoreAddOn.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureStoreAddOn

## SYNOPSIS
Gets the available Azure Store add-ons.

## SYNTAX

### ListAvailable
```
Get-AzureStoreAddOn [-ListAvailable] [[-Country] <String>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

### GetAddOn
```
Get-AzureStoreAddOn [[-Name] <String>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

Gets all the available add-ons for purchasing from the Azure Store, or gets the existing add-on instances for the current subscription.

## EXAMPLES

### Example 1
```
PS C:\>Get-AzureStoreAddOn
```

This example gets all purchased add-on instances for the current subscription.

### Example 2
```
PS C:\>Get-AzureStoreAddOn -ListAvailable
```

This example gets all the available add-ons for purchasing in United States from the Azure Store.

### Example 3
```
PS C:\>Get-AzureStoreAddOn -Name MyAddOn
```

This example gets an add-on named MyAddOn from the purchased add-on instance in the current subscription.

## PARAMETERS

### -ListAvailable
If specified, gets available add-ons for purchasing from the Azure Store.

```yaml
Type: SwitchParameter
Parameter Sets: ListAvailable
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Country
If specified, returns only the Azure Store add-on instances available in the specified country.
The default is "US".

```yaml
Type: String
Parameter Sets: ListAvailable
Aliases: 

Required: False
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Returns the add-on that matches the specified name.

```yaml
Type: String
Parameter Sets: GetAddOn
Aliases: 

Required: False
Position: 3
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
In-memory profile.```yaml
Type: AzureSMProfile
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

## NOTES

## RELATED LINKS

[New-AzureStoreAddOn](.\New-AzureStoreAddOn.md)

[Remove-AzureStoreAddOn](.\Remove-AzureStoreAddOn.md)

[Set-AzureStoreAddOn](.\Set-AzureStoreAddOn.md)

