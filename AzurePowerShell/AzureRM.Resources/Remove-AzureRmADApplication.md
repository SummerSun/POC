---
external help file: Microsoft.Azure.Commands.Resources.dll-Help.xml
online version: 
schema: 2.0.0
---

# Remove-AzureRmADApplication
## SYNOPSIS
Deletes the azure active directory application.

## SYNTAX

```
Remove-AzureRmADApplication -ApplicationObjectId <Guid> [-Force] [-WhatIf] [-Confirm]
```

## DESCRIPTION
Deletes the azure active directory application.

## EXAMPLES

### --------------------------  Delete AAD application.  --------------------------
@{paragraph=PS C:\\\>}

```
PS C:\> Remove-AzureRmADApplication -ApplicationObjectId b4cd1619-80b3-4cfb-9f8f-9f2333425738 -Force
```

Deletes the azure active directory application.

## PARAMETERS

### -ApplicationObjectId
@{Text=}

```yaml
Type: Guid
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Force
@{Text=}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
{{Fill Confirm Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
{{Fill WhatIf Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES
Keywords: azure, azurerm, arm, resource, management, manager, resource, group, template, deployment

## RELATED LINKS

[New-AzureRmADApplication]()

