---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: 
schema: 2.0.0
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/projects/azure-docs-powershell-int/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/Stop-AzureWebsite.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/projects/azure-docs-powershell-int/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/Stop-AzureWebsite.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Stop-AzureWebsite

## SYNOPSIS
Stops the specified website.

## SYNTAX

```
Stop-AzureWebsite [-PassThru] [[-Name] <String>] [-Slot <String>] [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

The Stop-AzureWebsite cmdlet stops the specified website hosted in Azure.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the website to stop.

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

### -Slot
Specifies the slot name of the website.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
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
Position: Named
Default value: None
Accept pipeline input: False
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

[Get-AzureWebsite](.\Get-AzureWebsite.md)
