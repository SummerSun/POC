---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 4ECF99B3-AFB5-49E1-A5BA-F1699A412F8E
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1..6.1/Get-AzureServiceProjectRoleRuntime.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1..6.1/Get-AzureServiceProjectRoleRuntime.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureServiceProjectRoleRuntime

## SYNOPSIS
Get the runtimes available to install in a role.

## SYNTAX

```
Get-AzureServiceProjectRoleRuntime [[-Runtime] <String>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

Gets the runtimes available to install in a role.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Runtime
The name of the runtime.
If a runtime specified, only the specific versions of that runtime available to install in your role in Windows Azure will be returned.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
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

[Add-AzureNodeWebRole](.\Add-AzureNodeWebRole.md)

[Add-AzureNodeWorkerRole](.\Add-AzureNodeWorkerRole.md)

[Set-AzureServiceProjectRole](.\Set-AzureServiceProjectRole.md)

[Set-AzureServiceProject](.\Set-AzureServiceProject.md)


