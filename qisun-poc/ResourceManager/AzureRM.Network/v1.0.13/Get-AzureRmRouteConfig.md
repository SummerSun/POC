---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureRmRouteConfig.md
schema: 2.0.0
ms.assetid: 2B08FCD6-BA8D-42B6-B9CC-897D26425669
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/Get-AzureRmRouteConfig.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/Get-AzureRmRouteConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmRouteConfig

## SYNOPSIS
Gets routes from a route table.

## SYNTAX

```
Get-AzureRmRouteConfig [-Name <String>] -RouteTable <PSRouteTable> [-InformationAction <ActionPreference>]
 [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmRouteConfig** cmdlet gets routes from an azure_2 route table.
You can specify a route by name.

## EXAMPLES

### Example 1: Get a route table
```
PS C:\>Get-AzureRmRouteTable -ResourceGroupName "ResourceGroup11" -Name "RouteTable01" | Get-AzureRmRouteConfig -Name "Route07"
Name              : route07
Id                : 
Etag              : 
ProvisioningState : 
AddressPrefix     : 10.1.0.0/16
NextHopType       : VnetLocal
NextHopIpAddress  :
```

This command gets the route table named RouteTable01 by using the **Get-AzureRmRouteTable** cmdlet.
The command passes that table to the current cmdlet by using the pipeline operator.
The current cmdlet gets the route named Route07 in the route table named RouteTable01.

## PARAMETERS

### -Name
Specifies the name of the route that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RouteTable
Specifies the route table from which this cmdlet gets routes.

```yaml
Type: PSRouteTable
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

## RELATED LINKS

[Add-AzureRmRouteConfig](.\Add-AzureRmRouteConfig.md)

[Get-AzureRmRouteTable](.\Get-AzureRmRouteTable.md)

[New-AzureRmRouteConfig](.\New-AzureRmRouteConfig.md)

[Remove-AzureRmRouteConfig](.\Remove-AzureRmRouteConfig.md)

[Set-AzureRmRouteConfig](.\Set-AzureRmRouteConfig.md)


