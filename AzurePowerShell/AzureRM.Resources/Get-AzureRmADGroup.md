---
external help file: Microsoft.Azure.Commands.Resources.dll-Help.xml
online version: 
schema: 2.0.0
---

# Get-AzureRmADGroup
## SYNOPSIS
Filters active directory groups.

## SYNTAX

### EmptyParameterSet (Default)
```
Get-AzureRmADGroup [-ObjectId <Guid>]
```

### SearchStringParameterSet
```
Get-AzureRmADGroup -SearchString <String>
```

### ObjectIdParameterSet
```
Get-AzureRmADGroup -ObjectId <Guid>
```

## DESCRIPTION
Filters active directory groups.

## EXAMPLES

### --------------------------  Filters groups using object id  --------------------------
@{paragraph=PS C:\\\>}

```
PS C:\> Get-AzureRmADGroup -ObjectId 85F89C90-780E-4AA6-9F4F-6F268D322EEE
```

Gets group with 85F89C90-780E-4AA6-9F4F-6F268D322EEE id

### --------------------------  Filters groups using Search String  --------------------------
@{paragraph=PS C:\\\>}

```
PS C:\> Get-AzureRmADGroup -SearchString Joe
```

Filters all ad groups that has Joe in the display name.

### --------------------------  List AD groups  --------------------------
@{paragraph=PS C:\\\>}

```
PS C:\> Get-AzureRmADGroup
```

Gets all AD groups

## PARAMETERS

### -ObjectId
Object id of the group.

```yaml
Type: Guid
Parameter Sets: EmptyParameterSet
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

```yaml
Type: Guid
Parameter Sets: ObjectIdParameterSet
Aliases: 

Required: True
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -SearchString
The group display name

```yaml
Type: String
Parameter Sets: SearchStringParameterSet
Aliases: 

Required: True
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmADUser]()

[Get-AzureRmADServicePrincipal]()

[Get-AzureRmADGroupMember]()

