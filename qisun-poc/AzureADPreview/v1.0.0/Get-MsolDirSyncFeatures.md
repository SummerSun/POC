---
external help file: Microsoft.Online.Administration.Automation.PSModule.dll-Help.xml
online version: .\Get-MsolDirSyncConfiguration.md
schema: 2.0.0
ms.assetid: F2ED75F9-4313-418D-8B3A-EED1DE39B9DB
updated_at: 10/19/2016 3:31 AM
ms.date: 10/19/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-azuread-int/blob/master/Azure%20AD%20Cmdlets/AzureADPreview/v1.0.0/Get-MsolDirSyncFeatures.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-azuread-int/blob/6a895a73e21f1df9572197497237f3a825ebd518/Azure%20AD%20Cmdlets/AzureADPreview/v1.0.0/Get-MsolDirSyncFeatures.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
ms.author: PowerShellHelpPub
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-MsolDirSyncFeatures

## SYNOPSIS
Gets the status of identity synchronization features for a tenant.

## SYNTAX

```
Get-MsolDirSyncFeatures [-Feature <String>] [-TenantId <Guid>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-MsolDirSyncProvisioningError** cmdlet gets the status of identity synchronization features for a tenant.

Synchronization features that can be used with this cmdlet include the following:

- DeviceWriteback
- DirectoryExtensions
- DuplicateProxyAddressResiliency
- DuplicateUPNResiliency
- EnableSoftMatchOnUpn
- PasswordSync
- SynchronizeUpnForManagedUsers
- UnifiedGroupWriteback
- UserWriteback

You can run this cmdlet without any feature being specified, in which case it will return a list of all enabled or disabled features.

## EXAMPLES

### Example 1: Get a list of all possible synchronization features
```
PS C:\>Get-MsolDirSyncFeatures
```

This command gets a list of all possible directory synchronization features and whether they are enabled or disabled.

### Example 2: Get a list of all possibleCheck whether the password PasswordSync synchronization features is enabledCheck whether the password is enabled
```
PS C:\>Get-MsolDirSyncFeatures -Feature PasswordSync
```

This command checks whether the password synchronization feature is enabled for the tenant.

## PARAMETERS

### -Feature
Specifies the directory synchronization feature that this cmdlet gets the status of.

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

### -TenantId
Specifies the unique ID of the tenant to perform the operation on.
If you do not specify this parameter the cmdlet will use the ID of the current user.
This parameter is only applicable to partner users.

```yaml
Type: Guid
Parameter Sets: (All)
Aliases: 

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

[Get-MsolDirSyncConfiguration](xref:AzureADPreview/v1.0.0/Get-MsolDirSyncConfiguration.md)

[Get-MsolDirSyncProvisioningError](xref:AzureADPreview/v1.0.0/Get-MsolDirSyncProvisioningError.md)


