---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: .\New-AzureApplicationGateway.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/CmdletMDs/Get-AzureApplicationGateway.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/CmdletMDs/Get-AzureApplicationGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Get-AzureApplicationGateway

## SYNOPSIS
Gets an application gateway.

## SYNTAX

```
Get-AzureApplicationGateway [[-Name] <String>] [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureApplicationGateway** cmdlet gets an existing application gateway.

## EXAMPLES

### Example 1: Get an application gateway
```
PS C:\>Get-AzureApplicationGateway -Name "ApplicationGateway06"
```

This command gets the application gateway named ApplicationGateway06.

### Example 2: Get all application gateways
```
PS C:\>Get-AzureApplicationGateway
```

This command gets all the application gateways under your subscription.

## PARAMETERS

### -Name
Specifies the name of the application gateway that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 0
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

### Microsoft.Azure.Networking.ApplicationGatewayObjectModel.ApplicationGateway, IEnumerable<Microsoft.Azure.Networking.ApplicationGatewayObjectModel.ApplicationGateway>

## NOTES

## RELATED LINKS

[New-AzureApplicationGateway](.\New-AzureApplicationGateway.md)

[Remove-AzureApplicationGateway](.\Remove-AzureApplicationGateway.md)

[Start-AzureApplicationGateway](.\Start-AzureApplicationGateway.md)

[Stop-AzureApplicationGateway](.\Stop-AzureApplicationGateway.md)

[Update-AzureApplicationGateway](.\Update-AzureApplicationGateway.md)

