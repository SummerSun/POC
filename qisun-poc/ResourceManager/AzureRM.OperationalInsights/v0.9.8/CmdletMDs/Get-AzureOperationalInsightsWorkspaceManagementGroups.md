---
external help file: Microsoft.Azure.Commands.OperationalInsights.dll-Help.xml
online version: .\Get-AzureOperationalInsightsWorkspace.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.OperationalInsights/v0.9.8/CmdletMDs/Get-AzureOperationalInsightsWorkspaceManagementGroups.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.OperationalInsights/v0.9.8/CmdletMDs/Get-AzureOperationalInsightsWorkspaceManagementGroups.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Get-AzureOperationalInsightsWorkspaceManagementGroups

## SYNOPSIS
Gets the management groups that are connected to a workspace.

## SYNTAX

```
Get-AzureOperationalInsightsWorkspaceManagementGroups [-ResourceGroupName] <String> [-Name] <String>
 [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureOperationalInsightsWorkspaceManagementGroups** cmdlet gets the management groups that are connected to a workspace.

## EXAMPLES

### Example 1: Get management groups by workspace name
```
PS C:\>Get-AzureOperationalInsightsWorkspaceManagementGroups -ResourceGroupName "ContosoResourceGroup" -Name "MyWorkspace"
```

This command gets the management groups for the workspace named MyWorkspace in the resource group named ContosoResourceGroup.

### Example 2: Get management groups by using the pipeline
```
PS C:\>Get-AzureOperationalInsightsWorkspace -ResourceGroupName "ContosoResourceGroup" -Name "MyWorkspace" | Get-AzureOperationalInsightsWorkspaceManagementGroups
```

This command uses the Get-AzureOperationalInsightsWorkspace cmdlet to get the workspace named MyWorkspace, and then passes the workspace to the current cmdlet, which gets the management groups for that workspace.

## PARAMETERS

### -ResourceGroupName
Specifies the name of the Azure resource group that contains the management groups to get.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name of a workspace.
This cmdlet gets the management groups that are connected to the workspace that this parameter specifies.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureOperationalInsightsWorkspace](.\Get-AzureOperationalInsightsWorkspace.md)

