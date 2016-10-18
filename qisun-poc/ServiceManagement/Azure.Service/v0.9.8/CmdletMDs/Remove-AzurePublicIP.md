---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: .\Get-AzurePublicIP.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/CmdletMDs/Remove-AzurePublicIP.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/CmdletMDs/Remove-AzurePublicIP.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzurePublicIP

## SYNOPSIS
Removes Public IP configuration from an Azure virtual machine.

## SYNTAX

```
Remove-AzurePublicIP [[-PublicIPName] <String>] -VM <IPersistentVM> [-Profile <AzureProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzurePublicIP** cmdlet removes Public IP configuration from an Azure virtual machine.

## EXAMPLES

### Example 1: Remove Public IP configuration
```
PS C:\>Get-AzureVM -ServiceName "FTPInAzure" -Name "FTPInstance" | Remove-AzurePublicIP | Update-AzureVM
```

This command gets the virtual machine named FTPInstance in the service named FTPInAzure by using the Get-AzureVM cmdlet.
The command passes that virtual machine to the current cmdlet by using the pipeline operator.
The current cmdlet removes Public IP configuration from the virtual machine.
The command passes the virtual machine to the Update-AzureVM cmdlet, which implements your changes.

## PARAMETERS

### -PublicIPName
Specifies the Public IP name.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VM
Specifies the virtual machine from which this cmdlet removes Public IP configuration.

```yaml
Type: IPersistentVM
Parameter Sets: (All)
Aliases: InputObject

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureProfile
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

### Microsoft.WindowsAzure.Commands.ServiceManagement.Model.IPersistentVM

## NOTES

## RELATED LINKS

[Get-AzurePublicIP](.\Get-AzurePublicIP.md)

[Get-AzureVM](.\Get-AzureVM.md)

[Set-AzurePublicIP](.\Set-AzurePublicIP.md)

[Update-AzureVM](.\Update-AzureVM.md)

