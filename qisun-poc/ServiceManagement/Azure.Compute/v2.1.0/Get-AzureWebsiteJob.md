---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: .\Get-AzureWebsite.md
schema: 2.0.0
ms.assetid: 4DE0DA54-8A4D-46B3-8B95-BF5B26441B26
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v2.1.0/Get-AzureWebsiteJob.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v2.1.0/Get-AzureWebsiteJob.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureWebsiteJob

## SYNOPSIS
Gets the web jobs associated with a website

## SYNTAX

```
Get-AzureWebsiteJob [-JobName <String>] [-JobType <String>] [[-Name] <String>] [-Slot <String>]
 [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
Gets the web jobs associated with a website

## EXAMPLES

### --------------  Get specific web job info --------------
```
C:\PS>Get-AzureWebsiteJob -Name MyWebsite -JobName MyWebJob
```

Gets a web job called MyWebJob from MyWebsite production slot

### --------------  Get all web jobs for a website --------------
```
C:\PS>Get-AzureWebsiteJob -Name MyWebsite
```

Gets all web jobs associated with MyWebsite production slot

### --------------  Get all triggered web jobs --------------
```
C:\PS>Get-AzureWebsiteJob -Name MyWebsite -Slot staging -Type Triggered
```

Gets all triggered web jobs from staging slot of MyWebsite

## PARAMETERS

### -Name
The name of the Azure website

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

### -Slot
The slot name of the Azure website

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -JobName
The web job name

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -JobType
The web job type.
Can be 'triggered' or 'continuous'

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
In-memory profile.```yaml
Type: AzureSMProfile
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

[Get-AzureWebsite](.\Get-AzureWebsite.md)

[New-AzureWebsiteJob](.\New-AzureWebsiteJob.md)

[Remove-AzureWebsiteJob](.\Remove-AzureWebsiteJob.md)

[Start-AzureWebsiteJob](.\Start-AzureWebsiteJob.md)

[Stop-AzureWebsiteJob](.\Stop-AzureWebsiteJob.md)


