---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: .\Add-AzureDns.md
schema: 2.0.0
ms.assetid: F65D3505-9B07-457B-B3AF-48CB1F5BBA4B
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/Get-AzureDns.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/Get-AzureDns.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureDns

## SYNOPSIS
Gets the DNS settings for an Azure deployment.

## SYNTAX

```
Get-AzureDns [-DnsSettings <DnsSettings>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureDns** cmdlet gets the DNS settings for an Azure deployment.
The cmdlet returns the friendly name and IP address of the DNS server in a DNS settings object.

## EXAMPLES

### Example 1: Get DNS settings
```
PS C:\>Get-AzureDeployment -ServiceName "ContosoService" -Slot "Production" | Get-AzureDNS
```

This command uses the Get-AzureDeployment cmdlet to get the production deployment of the service named ContosoService.
The command passes that object to the current cmdlet by using the pipeline operator.
The current cmdlet gets the DNS settings.

## PARAMETERS

### -DnsSettings
Specifies a **DnsSettings** object.

```yaml
Type: DnsSettings
Parameter Sets: (All)
Aliases: InputObject

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Add-AzureDns](.\Add-AzureDns.md)

[Get-AzureDeployment](.\Get-AzureDeployment.md)

[New-AzureDns](.\New-AzureDns.md)

[Remove-AzureDns](.\Remove-AzureDns.md)

[Set-AzureDns](.\Set-AzureDns.md)

