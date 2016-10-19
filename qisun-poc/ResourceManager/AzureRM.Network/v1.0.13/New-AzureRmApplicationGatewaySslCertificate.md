---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureRmApplicationGatewaySslCertificate.md
schema: 2.0.0
ms.assetid: 5C828062-A9F9-4506-8CDD-11C4766104CE
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/New-AzureRmApplicationGatewaySslCertificate.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/New-AzureRmApplicationGatewaySslCertificate.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmApplicationGatewaySslCertificate

## SYNOPSIS
Creates an SSL certificate for an azure_2 application gateway.

## SYNTAX

```
New-AzureRmApplicationGatewaySslCertificate -Name <String> -CertificateFile <String> -Password <String>
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmApplicationGatewaySslCertificate** cmdlet creates an SSL certificate for an azure_2 application gateway.

## EXAMPLES

### Example 1: Create an SSL certificate for an Azure application gateway.
```
PS C:\>$Cert = New-AzureRmApplicationGatewaySslCertificate -Name "Cert01" -CertificateFile "D:\cert01.pfx" -Password "Password01"
```

This command creates a SSL certificate named Cert01 for the default application gateway and stores the result in the variable named $Cert.

## PARAMETERS

### -Name
Specifies the name of the SSL certificate that this cmdlet creates.

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

### -CertificateFile
Specifies the path of the .pfx file of the SSL certificate that this cmdlet creates.

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

### -Password
Specifies the password of the SSL that this cmdlet creates.

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

### System.String

## OUTPUTS

### Microsoft.Azure.Commands.Network.Models.PSApplicationGatewaySslCertificate

## NOTES

## RELATED LINKS

[Add-AzureRmApplicationGatewaySslCertificate](.\Add-AzureRmApplicationGatewaySslCertificate.md)

[Get-AzureRmApplicationGatewaySslCertificate](.\Get-AzureRmApplicationGatewaySslCertificate.md)

[Remove-AzureRmApplicationGatewaySslCertificate](.\Remove-AzureRmApplicationGatewaySslCertificate.md)

[Set-AzureRmApplicationGatewaySslCertificate](.\Set-AzureRmApplicationGatewaySslCertificate.md)

