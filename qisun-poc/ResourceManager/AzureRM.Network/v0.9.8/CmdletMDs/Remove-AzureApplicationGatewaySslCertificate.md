---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureApplicationGatewaySslCertificate.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/CmdletMDs/Remove-AzureApplicationGatewaySslCertificate.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/CmdletMDs/Remove-AzureApplicationGatewaySslCertificate.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Remove-AzureApplicationGatewaySslCertificate

## SYNOPSIS
Removes an SSL certificate from an Azure application gateway.

## SYNTAX

```
Remove-AzureApplicationGatewaySslCertificate -Name <String> -ApplicationGateway <PSApplicationGateway>
 [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureApplicationGatewaySslCertificate** cmdlet removes a Secure Sockets Layer (SSL) certificate from an Azure application gateway.

## EXAMPLES

### Example 1: Remove an SSL certificate from an application gateway
```
PS C:\>$AppGW = Get-AzureApplicationGateway -Name "ApplicationGateway01" -ResourceGroupName "ResourceGroup01"
PS C:\> Remove-AzureApplicationGatewaySslCertificate -ApplicationGateway $AppGW -Name "Cert02"
```

This command removes the SSL certificate named Cert02 from the application gateway named ApplicationGateway01.

## PARAMETERS

### -ApplicationGateway
Specifies the application gateway from which this cmdlet removes an SSL certificate.```yaml
Type: PSApplicationGateway
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Specifies the name of an SSL certificate that this cmdlet removes.

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

## NOTES

## RELATED LINKS

[Add-AzureApplicationGatewaySslCertificate](.\Add-AzureApplicationGatewaySslCertificate.md)

[Get-AzureApplicationGatewaySslCertificate](.\Get-AzureApplicationGatewaySslCertificate.md)

[New-AzureApplicationGatewaySslCertificate](.\New-AzureApplicationGatewaySslCertificate.md)

[Set-AzureApplicationGatewaySslCertificate](.\Set-AzureApplicationGatewaySslCertificate.md)

