---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: .\Get-AzureVNetGateway.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v1.0/CmdletMDs/Remove-AzureVNetGateway.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v1.0/CmdletMDs/Remove-AzureVNetGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Remove-AzureVNetGateway

## SYNOPSIS
Deletes a VPN gateway.

## SYNTAX

```
Remove-AzureVNetGateway [-VNetName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureVNetGateway** cmdlet deletes an existing virtual private network (VPN) gateway for a virtual network.

## EXAMPLES

### Example 1: Remove a virtual network gateway
```
PS C:\>Remove-AzureVNetGateway -VNetName "ContosoVN07"
```

This command removes the virtual network gateway from the virtual network named ContosoVN07.

## PARAMETERS

### -VNetName
Specifies the virtual network in which this cmdlet deletes the VPN gateway.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
ps_azureprofile_description

```yaml
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

[Get-AzureVNetGateway](.\Get-AzureVNetGateway.md)

[New-AzureVNetGateway](.\New-AzureVNetGateway.md)

[Reset-AzureVNetGateway](.\Reset-AzureVNetGateway.md)

[Resize-AzureVNetGateway](.\Resize-AzureVNetGateway.md)

[Set-AzureVNetGatewayKey](.\Set-AzureVNetGatewayKey.md)

