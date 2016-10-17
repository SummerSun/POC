---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: 
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/New-AzureServiceProject.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/New-AzureServiceProject.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# New-AzureServiceProject

## SYNOPSIS
Creates the required files and configuration (sometimes referred to as scaffolding) for a new service.

## SYNTAX

```
New-AzureServiceProject [-ServiceName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

The **New-AzureServiceProject** cmdlet creates the required files and configuration for a new Azure service in the current directory.

## EXAMPLES

### 1:
```
PS C:\>New-AzureServiceProject MyService1
```

This example creates scaffolding for a new Azure service named  ¢â‚¬Å"MyService1 ¢â‚¬Â in the current directory.

## PARAMETERS

### -ServiceName
Specifies the name of the service.
It determines the first section of the hostname for your service (for example, name.cloudapp.net), and the directory that will contain your service.
The name can contain only letters, digits, and the dash character (-).

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

[Set-AzureServiceProject](.\Set-AzureServiceProject.md)

[Set-AzureServiceProjectRole](.\Set-AzureServiceProjectRole.md)

