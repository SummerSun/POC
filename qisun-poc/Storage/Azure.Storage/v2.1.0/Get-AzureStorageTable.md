---
external help file: Microsoft.WindowsAzure.Commands.Storage.dll-Help.xml
online version: .\New-AzureStorageTable.md
schema: 2.0.0
ms.assetid: 5E8A9E67-AD04-4430-B057-A63CFB99585E
updated_at: 10/19/2016 3:33 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/Storage/Azure.Storage/v2.1.0/Get-AzureStorageTable.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/c0d1e448da01261236e9ece01ca5c2a98effbf31/azureps-cmdlets-docs/Storage/Azure.Storage/v2.1.0/Get-AzureStorageTable.md
ms.topic: reference
ms.prod: powershell
ms.technology: Azure PowerShell
author: visual-studio-china
ms.author: PowerShellHelpPub
keywords: powershell, cmdlet
manager: visual-studio-china
open_to_public_contributors: true
ms.service: Storage
---

# Get-AzureStorageTable

## SYNOPSIS
Lists the storage tables.

## SYNTAX

### TableName (Default)
```
Get-AzureStorageTable [[-Name] <String>] [-Context <AzureStorageContext>]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [-PipelineVariable <String>]
 [<CommonParameters>]
```

### TablePrefix
```
Get-AzureStorageTable -Prefix <String> [-Context <AzureStorageContext>] [-InformationAction <ActionPreference>]
 [-InformationVariable <String>] [-PipelineVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureStorageTable** cmdlet lists the storage tables associated with the storage account in Azure.

## EXAMPLES

### Example 1: List all Azure Storage tables
```
PS C:\>Get-AzureStorageTable
```

This command gets all storage tables for a Storage account.

### Example 2: List Azure Storage tables using a wildcard character
```
PS C:\>Get-AzureStorageTable -Name table*
```

This command uses a wildcard character to get storage tables whose name starts with table.

### Example 3: List Azure Storage tables using table name prefix
```
PS C:\>Get-AzureStorageTable -Prefix "table"
```

This command uses the *Prefix* parameter to get storage tables whose name starts with table.

## PARAMETERS

### -Name
Specifies the table name.
If the table name is empty, the cmdlet lists all the tables.
Otherwise, it lists all tables that match the specified name or the regular name pattern.

```yaml
Type: String
Parameter Sets: TableName
Aliases: N, Table

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Context
Specifies the storage context.
To create it, you can use the New-AzureStorageContext cmdlet.

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

### -Prefix
Specifies a prefix used in the name of the table or tables you want to get.
You can use this to find all tables that start with the same string, such as table.

```yaml
Type: String
Parameter Sets: TablePrefix
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PipelineVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: pv

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

[New-AzureStorageTable](xref:Storage/Azure.Storage/v2.1.0/New-AzureStorageTable.md)

[Remove-AzureStorageTable](xref:Storage/Azure.Storage/v2.1.0/Remove-AzureStorageTable.md)


