---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: .\Get-AzureVirtualNetworkGateway.md
schema: 2.0.0
ms.assetid: E6BCC1D2-6AE1-480B-8F98-F10E6F8DF204
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v1.6.1/Resize-AzureVirtualNetworkGateway.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v1.6.1/Resize-AzureVirtualNetworkGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Resize-AzureVirtualNetworkGateway

## SYNOPSIS
Resizes a virtual network gateway.

## SYNTAX

```
Resize-AzureVirtualNetworkGateway [-GatewayId] <String> [-GatewaySKU] <String> [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The Resize-AzureVirtualNetworkGateway cmdlet resizes a virtual network gateway.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -GatewayId
Specifies the ID of a gateway.

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

### -GatewaySKU
```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
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

[Get-AzureVirtualNetworkGateway](.\Get-AzureVirtualNetworkGateway.md)

[New-AzureVirtualNetworkGateway](.\New-AzureVirtualNetworkGateway.md)

[Remove-AzureVirtualNetworkGateway](.\Remove-AzureVirtualNetworkGateway.md)

[Reset-AzureVirtualNetworkGateway](.\Reset-AzureVirtualNetworkGateway.md)

