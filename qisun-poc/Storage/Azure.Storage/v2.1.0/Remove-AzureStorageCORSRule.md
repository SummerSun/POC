---
external help file: Microsoft.WindowsAzure.Commands.Storage.dll-Help.xml
online version: .\Get-AzureStorageCORSRule.md
schema: 2.0.0
ms.assetid: EA872C93-797E-49A5-8E97-640A56AADCEB
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/Storage/Azure.Storage/v2.1.0/Remove-AzureStorageCORSRule.md
original_content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/Storage/Azure.Storage/v2.1.0/Remove-AzureStorageCORSRule.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/Storage/Azure.Storage/v2.1.0/Remove-AzureStorageCORSRule.md
ms.topic: reference
ms.prod: powershell
ms.technology: Azure PowerShell
author: visual-studio-china
ms.author: PowerShellHelpPub
keywords: powershell, cmdlet
manager: visual-studio-china
open_to_public_contributors: True
ms.service: Storage
---

# Remove-AzureStorageCORSRule

## SYNOPSIS
Removes CORS for a Storage service.

## SYNTAX

```
Remove-AzureStorageCORSRule [-ServiceType] <StorageServiceType> [-Context <AzureStorageContext>]
 [-ServerTimeoutPerRequest <Int32>] [-ClientTimeoutPerRequest <Int32>] [-ConcurrentTaskCount <Int32>]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureStorageCORSRule** cmdlet removes Cross-Origin Resource Sharing (CORS) for an Azure Storage service.
This cmdlet deletes all CORS rules in a Storage service type.
The types of storage services for this cmdlet are Blob, Table, Queue, and File.

## EXAMPLES

### Example 1: Remove CORS rules for the blob service
```
PS C:\>Remove-AzureStorageCORSRule -ServiceType Blob
```

This command removes CORS rules for the Blob service type.

## PARAMETERS

### -ServiceType
Specifies the Azure Storage service type for which this cmdlet removes rules.
The acceptable values for this parameter are:

- Blob 
- Table 
- Queue 
- File

```yaml
Type: StorageServiceType
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Context
Specifies the Azure storage context.
To obtain the storage context, the New-AzureStorageContext cmdlet.

```yaml
Type: AzureStorageContext
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -ServerTimeoutPerRequest
Specifies the length of the time-out period for the server part of a request.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClientTimeoutPerRequest
Specifies the client-side time-out interval, in seconds, for one service request.
If the previous call fails in the specified interval, this cmdlet retries the request.
If this cmdlet does not receive a successful response before the interval elapses, this cmdlet returns an error.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConcurrentTaskCount
Specifies the maximum concurrent network calls.
You can use this parameter to limit the concurrency to throttle local CPU and bandwidth usage by specifying the maximum number of concurrent network calls.
The specified value is an absolute count and is not multiplied by the core count.
This parameter can help reduce network connection problems in low bandwidth environments, such as 100 kilobits per second.
The default value is 10.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
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

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureStorageCORSRule](xref:Storage/Azure.Storage/v2.1.0/Get-AzureStorageCORSRule.md)

[Set-AzureStorageCORSRule](xref:Storage/Azure.Storage/v2.1.0/Set-AzureStorageCORSRule.md)


