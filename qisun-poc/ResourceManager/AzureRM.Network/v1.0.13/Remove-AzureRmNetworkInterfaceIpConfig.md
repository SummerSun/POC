---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureRmNetworkInterfaceIpConfig.md
schema: 2.0.0
ms.assetid: 24176DC6-1A7C-4386-95AB-D393E7E041D4
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/Remove-AzureRmNetworkInterfaceIpConfig.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/Remove-AzureRmNetworkInterfaceIpConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmNetworkInterfaceIpConfig

## SYNOPSIS
Removes a network interface IP configuration from a network interface.

## SYNTAX

```
Remove-AzureRmNetworkInterfaceIpConfig -Name <String> -NetworkInterface <PSNetworkInterface>
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmNetworkInterfaceIpConfig** cmdlet removes a network interface IP configuration from an azure_2 network interface.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the network interface IP configuration to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NetworkInterface
Specifies a **NetworkInterface** object.
This object contains the network interface IP configuration to remove.

```yaml
Type: PSNetworkInterface
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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
* Keywords: azure, azurerm, arm, resource, management, manager, network, networking

## RELATED LINKS

[Add-AzureRmNetworkInterfaceIpConfig](.\Add-AzureRmNetworkInterfaceIpConfig.md)

[Get-AzureRmNetworkInterfaceIpConfig](.\Get-AzureRmNetworkInterfaceIpConfig.md)

[New-AzureRmNetworkInterfaceIpConfig](.\New-AzureRmNetworkInterfaceIpConfig.md)

[Set-AzureRmNetworkInterfaceIpConfig](.\Set-AzureRmNetworkInterfaceIpConfig.md)


