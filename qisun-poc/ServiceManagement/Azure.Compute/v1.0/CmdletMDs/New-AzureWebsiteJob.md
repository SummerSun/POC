---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: .\New-AzureWebsite.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/New-AzureWebsiteJob.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.0/CmdletMDs/New-AzureWebsiteJob.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# New-AzureWebsiteJob

## SYNOPSIS
Creates new web job for a website

## SYNTAX

```
New-AzureWebsiteJob -JobName <String> -JobType <WebJobType> -JobFile <String> [[-Name] <String>]
 [-Slot <String>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
Creates new web job for a website

## EXAMPLES

### --------------  Create new web job for a website --------------
```
C:\PS>New-AzureWebsiteJob -Name MyWebsite -JobName MyWebJob -JobType Continuous -JobFile job.bat
```

Creates a continuous job to call job.bat on website MyWebsite

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

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -JobType
The web job type.
Can be 'triggered' or 'continuous'

```yaml
Type: WebJobType
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -JobFile
The web job file

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
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

[New-AzureWebsite](.\New-AzureWebsite.md)

[Get-AzureWebsiteJob](.\Get-AzureWebsiteJob.md)

[Remove-AzureWebsiteJob](.\Remove-AzureWebsiteJob.md)

[Start-AzureWebsiteJob](.\Start-AzureWebsiteJob.md)

[Stop-AzureWebsiteJob](.\Stop-AzureWebsiteJob.md)

