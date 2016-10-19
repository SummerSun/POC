---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: .\Get-AzureApplicationGateway.md
schema: 2.0.0
ms.assetid: 0079028F-32BD-4F37-AA6A-C578E7AC8D79
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/Update-AzureApplicationGateway.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/Update-AzureApplicationGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Update-AzureApplicationGateway

## SYNOPSIS
Updates an application gateway.

## SYNTAX

```
Update-AzureApplicationGateway [-Name] <String> [[-VnetName] <String>]
 [[-Subnets] <System.Collections.Generic.List`1[System.String]>] [[-InstanceCount] <UInt32>]
 [[-GatewaySize] <String>] [[-Description] <String>] [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Update-AzureApplicationGateway** cmdlet updates an existing application gateway.

## EXAMPLES

### Example 1: Modify an application gateway by using its name
```
PS C:\>Stop-AzureApplicationGateway -Name "ApplicationGateway06"
PS C:\> Update-AzureApplicationGateway -Name "ApplicationGateway06" -VnetName "VirutalNetwork18" -Subnets @("Subnet05", "Subnet06")
```

The first command stops the application gateway named ApplicationGateway06.
An application gateway must be stopped before you can modify the virtual network or subnets.

The second command modifies the virtual subnet and subnets for the application gateway named ApplicationGateway06.

### Example 2: Modify additional properties of an application gateway
```
PS C:\>Update-AzureApplicationGateway -Name "ApplicationGateway06" -InstanceCount 2 -GatewaySize "Large" -Description "Updated application gateway"
```

This command modifies the instance count, gateway size, and description for the application gateway named ApplicationGateway06.
This command does not modify the virtual network or subnets for the application gateway.
Therefore, you do not have to stop the application gateway before you run this command.

### Example 3: Modify an application gateway by using the pipeline
```
PS C:\>$ApplicationGateway = Get-AzureApplicationGateway -Name "ApplicationGateway06"
PS C:\> $ApplicationGateway.GatewaySize = "Medium"
PS C:\> $ApplicationGateway | Update-AzureApplicationGateway
```

The first command gets the application gateway named ApplicationGateway06 by using the **Get-AzureApplicationGateway** cmdlet.
The command stores it in the $ApplicationGateway variable.

The second command assigns the **GatewaySize** property the value Medium.

The final command passes the updated $ApplicationGateway to the current cmdlet.

## PARAMETERS

### -Name
Specifies the name of the application gateway that this cmdlet updates.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -VnetName
Specifies the virtual network in which this cmdlet deploys the application gateway.

You cannot update a virtual network while the application gateway is running.
To stop the application gateway, use **Stop-AzureApplicationGateway**.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Subnets
Specifies an array of subnets in which this cmdlet deploys the application gateway.

You cannot update subnets while the application gateway is running.
To stop the application gateway, use the Stop-AzureApplicationGateway cmdlet.

```yaml
Type: System.Collections.Generic.List`1[System.String]
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -InstanceCount
Specifies the number of instances that this cmdlet assigns to the application gateway.

```yaml
Type: UInt32
Parameter Sets: (All)
Aliases: 

Required: False
Position: 3
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -GatewaySize
Specifies the size that this cmdlet assigns to the application gateway.
Valid values are: 

- Small 
- Medium
- Large

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 4
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Description
Specifies a description that this cmdlet assigns to the application gateway.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 5
Default value: None
Accept pipeline input: True (ByPropertyName)
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

### System.String

## OUTPUTS

### Microsoft.WindowsAzure.Management.ApplicationGateway.Models.ApplicationGatewayOperationResponse

## NOTES

## RELATED LINKS

[Get-AzureApplicationGateway](..\..\..\..\ResourceManager\AzureRM.Network\v0.9.8\CmdletMDs\Get-AzureApplicationGateway.md)

[New-AzureApplicationGateway](..\..\..\..\ResourceManager\AzureRM.Network\v0.9.8\CmdletMDs\New-AzureApplicationGateway.md)

[Remove-AzureApplicationGateway](..\..\..\..\ResourceManager\AzureRM.Network\v0.9.8\CmdletMDs\Remove-AzureApplicationGateway.md)

[Start-AzureApplicationGateway](..\..\..\..\ResourceManager\AzureRM.Network\v0.9.8\CmdletMDs\Start-AzureApplicationGateway.md)

[Stop-AzureApplicationGateway](..\..\..\..\ResourceManager\AzureRM.Network\v0.9.8\CmdletMDs\Stop-AzureApplicationGateway.md)

