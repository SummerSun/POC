---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureRmApplicationGatewayIPConfiguration.md
schema: 2.0.0
ms.assetid: 3ECE5B86-74D0-4E88-8080-8E19295B62CD
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/New-AzureRmApplicationGatewayIPConfiguration.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/New-AzureRmApplicationGatewayIPConfiguration.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmApplicationGatewayIPConfiguration

## SYNOPSIS
Creates an IP configuration for an application gateway.

## SYNTAX

### SetByResourceId
```
New-AzureRmApplicationGatewayIPConfiguration -Name <String> [-SubnetId <String>]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

### SetByResource
```
New-AzureRmApplicationGatewayIPConfiguration -Name <String> [-Subnet <PSSubnet>]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmApplicationGatewayIPConfiguration** cmdlet creates an IP configuration for an application gateway.
The IP configuration contains the subnet in which application gateway is deployed.

## EXAMPLES

### Example 1: Create an IP configuration for an application gateway.
```
PS C:\>$VNet = Get-AzureRmvirtualNetwork -Name "VNet01" -ResourceGroupName "ResourceGroup01"
PS C:\> $Subnet = Get-AzureRmVirtualNetworkSubnetConfig -Name "Subnet01" -VirtualNetwork $VNet 
PS C:\ $GatewayIpConfig = New-AzureRmApplicationGatewayIPConfiguration -Name "AppGwSubnet01" -Subnet $Subnet
```

The first command gets a virtual network named VNet01 that belongs to the resource group named ResourceGroup01.

The second command gets the subnet configuration for the subnet that the virtual network in the previous command belongs to, and stores it in the $Subnet variable.

The third command creates the IP configuration using $Subnet.

## PARAMETERS

### -Name
Specifies the name of the IP configuration to create.

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

### -SubnetId
Specifies the subnet ID.
This is the subnet in which the application gateway would be deployed.

```yaml
Type: String
Parameter Sets: SetByResourceId
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
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

### -Subnet
Specifies the subnet object.
This is the subnet in which the application gateway is deployed.

```yaml
Type: PSSubnet
Parameter Sets: SetByResource
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

### System.String

## OUTPUTS

### Microsoft.Azure.Commands.Network.Models.PSApplicationGatewayIPConfiguration

## NOTES

## RELATED LINKS

[Add-AzureRmApplicationGatewayIPConfiguration](.\Add-AzureRmApplicationGatewayIPConfiguration.md)

[Get-AzureRmApplicationGatewayIPConfiguration](.\Get-AzureRmApplicationGatewayIPConfiguration.md)

[Remove-AzureRmApplicationGatewayIPConfiguration](.\Remove-AzureRmApplicationGatewayIPConfiguration.md)

[Set-AzureRmApplicationGatewayIPConfiguration](.\Set-AzureRmApplicationGatewayIPConfiguration.md)

