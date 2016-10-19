---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureLoadBalancerRuleConfig.md
schema: 2.0.0
ms.assetid: F1A03313-C12D-4ACB-BF22-CBEDB475B8A9
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/Remove-AzureLoadBalancerRuleConfig.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/Remove-AzureLoadBalancerRuleConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureLoadBalancerRuleConfig

## SYNOPSIS
Removes a rule configuration for a load balancer.

## SYNTAX

```
Remove-AzureLoadBalancerRuleConfig [-Name <String>] -LoadBalancer <PSLoadBalancer> [-Profile <AzureProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureLoadBalancerRuleConfig** cmdlet removes a rule configuration for an Azure load balancer.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -LoadBalancer
Specifies the **LoadBalancer** object that contains the rule configuration to remove.

```yaml
Type: PSLoadBalancer
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Specifies the name of the load balancer rule configuration to remove.

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

### -Profile
Specifies an Azure profile.

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

## NOTES

## RELATED LINKS

[Add-AzureLoadBalancerRuleConfig](.\Add-AzureLoadBalancerRuleConfig.md)

[Get-AzureLoadBalancerRuleConfig](.\Get-AzureLoadBalancerRuleConfig.md)

[New-AzureLoadBalancerRuleConfig](.\New-AzureLoadBalancerRuleConfig.md)

[Set-AzureLoadBalancerRuleConfig](.\Set-AzureLoadBalancerRuleConfig.md)


