---
external help file: RMAzure_Apimanagement.xml
online version: e067ded3-a2e3-4d53-8628-0ebbafa62721
schema: 2.0.0
updated_at: 9/8/2016 10:40 AM
ms.date: 9/8/2016
ms.topic: reference
content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Resource%20Manager/API%20Management%20Cmdlets/v1.0/Backup-AzureRmApiManagement.md
original_content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Resource%20Manager/API%20Management%20Cmdlets/v1.0/Backup-AzureRmApiManagement.md
gitcommit: https://github.com/azure/azure-docs-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Resource%20Manager/API%20Management%20Cmdlets/v1.0/Backup-AzureRmApiManagement.md
---

# Backup-AzureRmApiManagement
## SYNOPSIS
Backs up an API Management service.

## SYNTAX

```
Backup-AzureRmApiManagement [-PassThru] [-TargetBlobName <String>] -Name <String> -ResourceGroupName <String>
 -StorageContext <AzureStorageContext> -TargetContainerName <String>
```

## DESCRIPTION
The **Backup-AzureRmApiManagement** cmdlet backs up an instance of an azure_2 API Management service.
This cmdlet stores the backup as an azure_2 Storage blob.

## EXAMPLES

### Example 1: Back up an API Management service
```
PS C:\>Backup-AzureRmApiManagement -ResourceGroupName "ContosoGroup02" -Name "ContosoApi" -StorageContext $StorageContext -TargetContainerName "ContosoBackups" -TargetBlobName "ContosoBackup.apimbackup"
```

This command backs up an API Management service to a Storage blob.

## PARAMETERS

### -Name
Specifies the name of the API Management deployment that this cmdlet backs up.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -PassThru
Indicates that this cmdlet returns the backed up **PsApiManagement** object, if the operation succeeds.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the of resource group under which the API Management deployment exists.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -StorageContext
Specifies a storage connection context.

```yaml
Type: AzureStorageContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True(ByPropertyName)
Accept wildcard characters: False
```

### -TargetBlobName
Specifies the name of the blob for the backup.
If the blob does not exist, this cmdlet creates it.
This cmdlet generates a default value based on the following pattern: 

{Name}-{yyyy-MM-dd-HH-mm}.apimbackup

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TargetContainerName
Specifies the name of the container of the blob for the backup.
If the container does not exist, this cmdlet creates it.

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

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmApiManagement](e067ded3-a2e3-4d53-8628-0ebbafa62721)

[New-AzureRmApiManagement](6b5595ca-246e-4381-a37e-24dfae307109)

[Remove-AzureRmApiManagement](9a2c4617-9870-4d9c-92fa-2af03211d931)

[Restore-AzureRmApiManagement](b0ff412d-269a-472f-8d79-9c0b9f0ebac2)

