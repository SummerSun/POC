---
external help file: Microsoft.Azure.Commands.Compute.dll-Help.xml
online version: .\Get-AzureRmVM.md
schema: 2.0.0
ms.assetid: 25E51DF6-3D1B-4187-94C8-53B31F0B6920
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v1.3.4/Remove-AzureRmVMNetworkInterface.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v1.3.4/Remove-AzureRmVMNetworkInterface.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmVMNetworkInterface

## SYNOPSIS
Removes a network interface from a virtual machine.

## SYNTAX

```
Remove-AzureRmVMNetworkInterface [-VM] <PSVirtualMachine> [-NetworkInterfaceIDs] <String[]>
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmVMNetworkInterface** cmdlet removes a network interface from a virtual machine.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -VM
Specifies the virtual machine from which this cmdlet removes a network interface.
To obtain a virtual machine object, use the Get-AzureRmVM cmdlet.

```yaml
Type: PSVirtualMachine
Parameter Sets: (All)
Aliases: VMProfile

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -NetworkInterfaceIDs
Specifies an array of network interface IDs that this cmdlet removes.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Id, NicIds

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

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

[Get-AzureRmVM](.\Get-AzureRmVM.md)

