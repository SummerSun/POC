---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Get-AzureNetworkSecurityGroup.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/CmdletMDs/Set-AzureNetworkSecurityGroup.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/CmdletMDs/Set-AzureNetworkSecurityGroup.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Set-AzureNetworkSecurityGroup

## SYNOPSIS
Sets the goal state for a network security group.

## SYNTAX

```
Set-AzureNetworkSecurityGroup -NetworkSecurityGroup <PSNetworkSecurityGroup> [-Profile <AzureProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureNetworkSecurityGroup** cmdlet sets the goal state for an Azure network security group.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -NetworkSecurityGroup
A Network Security Group object representing the goal state to which the Network Security Group should be set.

```yaml
Type: PSNetworkSecurityGroup
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

[Get-AzureNetworkSecurityGroup](.\Get-AzureNetworkSecurityGroup.md)

[New-AzureNetworkSecurityGroup](.\New-AzureNetworkSecurityGroup.md)

[Remove-AzureNetworkSecurityGroup](.\Remove-AzureNetworkSecurityGroup.md)

