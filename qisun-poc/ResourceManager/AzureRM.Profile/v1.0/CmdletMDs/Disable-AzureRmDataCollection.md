---
external help file: Microsoft.Azure.Commands.Profile.dll-Help.xml
online version: .\Enable-AzureRmDataCollection.md
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Profile/v1.0/CmdletMDs/Disable-AzureRmDataCollection.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ResourceManager/AzureRM.Profile/v1.0/CmdletMDs/Disable-AzureRmDataCollection.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Disable-AzureRmDataCollection

## SYNOPSIS
Disables collection of data to improve user experience.

## SYNTAX

```
Disable-AzureRmDataCollection [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **Disable-AzureRmDataCollection** cmdlet disables collection of data to improve the user experience with APS cmdlets.

APS does not collect data unless you explicitly opt in, either by using the Enable-AzureRmDataCollection cmdlet or when APS prompts you about collecting data the first time that you run a cmdlet.

If you run the current cmdlet before you run any APS cmdlets, APS does not prompt you about data collection the first time that you run a cmdlet.

To enable data collection for the current user, run **Enable-AzureRmDataCollection**.

## EXAMPLES

### Example 1: Disable data collection
```
PS C:\>Disable-AzureRmDataCollection
```

This command disables data collection for the current user on the current computer.

## PARAMETERS

### -Confirm
psdx_confirmdesc

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
psdx_whatifdesc

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Enable-AzureRmDataCollection](.\Enable-AzureRmDataCollection.md)

