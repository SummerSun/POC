---
external help file: Microsoft.Azure.Commands.DataFactories.dll-Help.xml
online version: 7a828f4d-bcad-4c9a-8a41-ea9bedde2552
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.DataFactories/v0.9.8/CmdletMDs/Suspend-AzureDataFactoryPipeline.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.DataFactories/v0.9.8/CmdletMDs/Suspend-AzureDataFactoryPipeline.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Suspend-AzureDataFactoryPipeline

## SYNOPSIS
Suspends the specified pipeline in an Azure data factory.

## SYNTAX

### ByFactoryName (Default)
```
Suspend-AzureDataFactoryPipeline [-Force] [-Name] <String> [-DataFactoryName] <String>
 [-ResourceGroupName] <String> [-Profile <AzureProfile>] [<CommonParameters>]
```

### ByFactoryObject
```
Suspend-AzureDataFactoryPipeline [-Force] [-Name] <String> [-DataFactory] <PSDataFactory>
 [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The Suspend-AzureDataFactoryPipeline cmdlet suspends the specified pipeline in an Azure data factory.
You can resume the pipeline later by using the Resume-AzureDataFactoryPipeline cmdlet.

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
PS C:\> Suspend-AzureDataFactoryPipeline -Name DPWikiSample -DataFactoryName WikiADF -ResourceGroupName ADF
```

Suspends the pipeline 'DPWikiSample' in the Azure data factory 'WikiADF'.

## PARAMETERS

### -DataFactory
Specifies a  object.
This cmdlet suspends a pipeline that belongs to the data factory that this parameter specifies.

```yaml
Type: PSDataFactory
Parameter Sets: ByFactoryObject
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -DataFactoryName
Name of the data factory.

```yaml
Type: String
Parameter Sets: ByFactoryName
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Force
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

### -Name
Name of the pipeline.

```yaml
Type: String
Parameter Sets: (All)
Aliases: PipelineName

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Name of the resource group.

```yaml
Type: String
Parameter Sets: ByFactoryName
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
@{Text=}

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

## OUTPUTS

### System.Boolean

## NOTES

## RELATED LINKS

