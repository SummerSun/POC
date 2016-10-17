---
external help file: Microsoft.Azure.Commands.HDInsight.dll-Help.xml
online version: .\New-AzureHDInsightHiveJobDefinition.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.HDInsight/v0.9.8/CmdletMDs/Use-AzureHDInsightCluster.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.HDInsight/v0.9.8/CmdletMDs/Use-AzureHDInsightCluster.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Use-AzureHDInsightCluster

## SYNOPSIS
Selects a cluster to be used with the Invoke-AzureHDInsightHiveJob cmdlet

## SYNTAX

```
Use-AzureHDInsightCluster [-ResourceGroupName] <String> [-ClusterName] <String>
 [-ClusterCredential] <PSCredential> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Use-AzureHDInsightCluster** cmdlet selects the Azure HDInsight cluster for the Invoke-AzureHDInsightHiveJob cmdlet to use to submit jobs.

## EXAMPLES

### Example 1: Select a cluster for Hive query submission.
```
PS C:\> # Cluster info
        $clusterResourceGroupName = "Group"
        $clusterName = "your-hadoop-001"
        $clusterCreds = Get-Credential
        
        Use-AzureHDInsightCluster -ResourceGroupName $clusterResourceGroupName `
            -ClusterName $clusterName `
            -ClusterCredential $clusterCreds
```

## PARAMETERS

### -ClusterCredential
The credentials with which to connect to the cluster.```yaml
Type: PSCredential
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClusterName
Gets or sets the name of the cluster.```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

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

### -ResourceGroupName
Gets or sets the name of the resource group.```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
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

[New-AzureHDInsightHiveJobDefinition](.\New-AzureHDInsightHiveJobDefinition.md)

[Invoke-AzureHDInsightHiveJob](.\Invoke-AzureHDInsightHiveJob.md)

[Azure HDInsight Cmdlets](.\AzureRM.HDInsight.md)

