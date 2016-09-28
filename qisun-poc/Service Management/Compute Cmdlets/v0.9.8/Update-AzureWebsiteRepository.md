---
external help file: SMAzure_Compute.xml
online version: 0c2a5092-db45-4ce7-b39b-d1e499b4a867
schema: 2.0.0
updated_at: 9/28/2016 10:45 AM
ms.date: 9/28/2016
ms.topic: reference
source_repo: https://github.com/SummerSun/poc-azure-powershell.git
source_branch: master
gitcommit: https://github.com/SummerSun/poc-azure-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v0.9.8/Update-AzureWebsiteRepository.md
---

# Update-AzureWebsiteRepository
## SYNOPSIS
Update the remote repositories of a local git repository for all the slots

## SYNTAX

```
Update-AzureWebsiteRepository [[-Name] <String>] -PublishingUsername <String> [-Confirm] [-WhatIf]
```

## DESCRIPTION
Update the remote repositories of a local git repository for all the slots

## EXAMPLES

### --------------  Update Website Remote Repositories --------------
```
C:\PS>Update-AzureWebsiteRepository -Name MyWebsite
```

Updates the remote repositories of a local git repository for all the slots for website MyWebsite

## PARAMETERS

### -Name
The name of the website

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PublishingUsername
The username you have specified in the Microsoft Azure Portal for Git deployment

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureWebsite](0c2a5092-db45-4ce7-b39b-d1e499b4a867)

[New-AzureWebsite](498c1abd-298b-43e9-ac53-bc57054a5387)

[Start-AzureWebsite](d6ee400f-4a92-4f2f-83bb-70188bb2000d)

[Stop-AzureWebsite](62c5de93-e58b-4e57-85d0-8b7e75df1f31)
