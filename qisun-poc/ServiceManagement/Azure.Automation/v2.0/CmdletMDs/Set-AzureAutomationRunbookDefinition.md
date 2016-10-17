---
external help file: Microsoft.Azure.Commands.Automation.dll-Help.xml
online version: http://go.microsoft.com/fwlink/?LinkId=397916
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v2.0/CmdletMDs/Set-AzureAutomationRunbookDefinition.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v2.0/CmdletMDs/Set-AzureAutomationRunbookDefinition.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Set-AzureAutomationRunbookDefinition

## SYNOPSIS
Updates the draft definition of a runbook.

## SYNTAX

```
Set-AzureAutomationRunbookDefinition [-Name] <String> [-Path] <String> [-Overwrite]
 [-AutomationAccountName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureAutomationRunbookDefinition** cmdlet updates the draft definition of a Microsoft Azure Automation runbook.
Specify a Windows PowerShell ‚Â® script (.ps1) file that contains a runbook that becomes the draft runbook.

If a draft definition already exists, use the *Overwrite* parameter to force the cmdlet to overwrite the existing draft.

## EXAMPLES

### Example 1: Overwrite an existing draft definition of a runbook
```
PS C:\> Set-AzureAutomationRunbookDefinition -AutomationAccountName "Contoso17" -Name "Runbk01" -Path ".\App01.ps1" -Overwrite
```

This command overwrites the existing draft definition of a runbook.

## PARAMETERS

### -AutomationAccountName
Specifies the name of an Automation account.

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

### -Name
Specifies a name.

```yaml
Type: String
Parameter Sets: (All)
Aliases: RunbookName

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Overwrite
Indicates whether to overwrite an existing draft definition.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Path
Specifies the path to a runbook.

```yaml
Type: String
Parameter Sets: (All)
Aliases: RunbookPath

Required: True
Position: 3
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
@{Text=}

```yaml
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

### Microsoft.Azure.Commands.Automation.Model.RunbookDefinition

## NOTES

## RELATED LINKS

[Get-AzureAutomationRunbookDefinition](.\Get-AzureAutomationRunbookDefinition.md)

