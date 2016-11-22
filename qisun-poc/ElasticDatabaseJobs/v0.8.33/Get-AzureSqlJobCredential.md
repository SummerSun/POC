---
external help file: Microsoft.Azure.SqlDatabase.Jobs.PowerShell.dll-Help.xml
online version:
schema: 2.0.0
ms.assetid: 43FAC986-8E46-47B5-9BDD-21C65C5DE7E5
updated_at: 11/17/2016 5:33 AM
ms.date: 11/17/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ElasticDatabaseJobs/v0.8.33/Get-AzureSqlJobCredential.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/2692a7998846b66d06a416c56978167da402f8d5/azureps-cmdlets-docs/ElasticDatabaseJobs/v0.8.33/Get-AzureSqlJobCredential.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
ms.author: PowerShellHelpPub
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureSqlJobCredential

## SYNOPSIS
Gets one or multiple database credentials to use when connecting to databases for execution of jobs.

## SYNTAX

### All (Default)
```
Get-AzureSqlJobCredential [[-AzureSqlJobConnection] <AzureSqlJobConnection>] [<CommonParameters>]
```

### CredentialName
```
Get-AzureSqlJobCredential -CredentialName <String[]> [[-AzureSqlJobConnection] <AzureSqlJobConnection>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureSqlJobCredential** cmdlet gets one or multiple database credentials to use when connecting to databases for execution of jobs.
Passwords are encrypted prior to transmission within creation and are not returned through get requests.

## EXAMPLES

### Example 1: Get the credential stored within the system using the provided name
```
PS C:\>Get-AzureSqlJobCredential -CredentialName MyCredential
CredentialName                                              UserName
--------------                                              --------
MyCredential                                                MyUsername
```

This command gets the credential stored within the system using the provided name.

### Example 2: Get all credentials stored within the system
```
PS C:\>Get-AzureSqlJobCredential
CredentialName                                              UserName
--------------                                              --------
MyCredential                                                MyUsername
MyCredential2                                               MyUsername2
```

Get all credentials stored within the system.

## PARAMETERS

### -AzureSqlJobConnection
Specifies the connection state object for the job.
You can get the connection state object through the N[ew-AzureSqlJobConnection](./New-AzureSqlJobConnection.md) cmdlet.
If you do not specify this parameter, the connection state is used from a prior call to the [Use-AzureSqlJobConnection](./Use-AzureSqlJobConnection.md) cmdlet.

```yaml
Type: AzureSqlJobConnection
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CredentialName
Specifies the name of the credential.

```yaml
Type: String[]
Parameter Sets: CredentialName
Aliases:

Required: True
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

[New-AzureSqlJobCredential](xref:ElasticDatabaseJobs/v0.8.33/New-AzureSqlJobCredential.md)

[Use-AzureSqlJobConnection](xref:ElasticDatabaseJobs/v0.8.33/Use-AzureSqlJobConnection.md)

[Set-AzureSqlJobCredential](xref:ElasticDatabaseJobs/v0.8.33/Set-AzureSqlJobCredential.md)
