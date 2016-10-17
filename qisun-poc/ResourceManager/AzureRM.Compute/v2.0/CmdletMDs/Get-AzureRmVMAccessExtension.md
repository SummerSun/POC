---
external help file: Microsoft.Azure.Commands.Compute.dll-Help.xml
online version: .\Remove-AzureRmVMAccessExtension.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v2.0/CmdletMDs/Get-AzureRmVMAccessExtension.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v2.0/CmdletMDs/Get-AzureRmVMAccessExtension.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Get-AzureRmVMAccessExtension

## SYNOPSIS
Gets information about the VMAccess extension.

## SYNTAX

```
Get-AzureRmVMAccessExtension [-ResourceGroupName] <String> [-VMName] <String> [-Name] <String> [-Status]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmVMAccessExtension** cmdlet gets information about the Virtual Machine Access (VMAccess) Virtual Machine Extension.

## EXAMPLES

### Example 1: Get the VMAccess extension
```
PS C:\>$VMAccessExtension = Get-AzureRmVMAccessExtension -ResourceGroupName "ResourceGroup11" -VMName "VirtualMachine07" -Name "ContosoTest"
```

This command gets the VMAccess extension named ContosoTest for the virtual machine named VirtualMachine07.

### Example 2: Get the instance view of the VMAccess extension
```
PS C:\>$VMAccessExtension = Get-AzureRmVMAccessExtension -ResourceGroupName "ResourceGroup11" -VMName "VirtualMachine07" -Name "ContosoTest" -Status
```

This command gets the instance view of the VMAccess extension named ContosoTest for the virtual machine named VirtualMachine07.

## PARAMETERS

### -Name
Specifies the name of the extension that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ExtensionName

Required: True
Position: 3
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group of the virtual machine.

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

### -Status
Indicates that this cmdlet gets only the instance view of the extension.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: 4
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -VMName
Specifies the name of a virtual machine.
This cmdlet gets information about VMAccess for the virtual machine that this parameter specifies.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ResourceName

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Remove-AzureRmVMAccessExtension](.\Remove-AzureRmVMAccessExtension.md)

[Set-AzureRmVMAccessExtension](.\Set-AzureRmVMAccessExtension.md)

[Get-AzureRmVMExtension](.\Get-AzureRmVMExtension.md)

