---
external help file: Microsoft.AzureStack.Commands.dll-Help.xml
online version: 
schema: 2.0.0
---

# Get-AzureRMPlan
## SYNOPSIS
Gets the list of all Plans in the system.
When the Plan Name is mentioned, it fetches the specific Plan.
This cmdlet is applicable only to Microsoft Azure Stack Environments

## SYNTAX

### TenantList (Default)
```
Get-AzureRMPlan [-AdminUri <Uri>] [-Token <String>] [-ApiVersion <String>] [-DisableCertificateValidation]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>]
```

### TenantGet
```
Get-AzureRMPlan -Name <String> [-AdminUri <Uri>] [-Token <String>] [-ApiVersion <String>]
 [-DisableCertificateValidation] [-InformationAction <ActionPreference>] [-InformationVariable <String>]
```

### Admin
```
Get-AzureRMPlan [-Name <String>] -ResourceGroup <String> [-SubscriptionId <Guid>] [-Managed] [-AdminUri <Uri>]
 [-Token <String>] [-ApiVersion <String>] [-DisableCertificateValidation]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>]
```

## DESCRIPTION

## EXAMPLES

### Example 1
```
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AdminUri
URI of the Azure Resource Manager endpoint

```yaml
Type: Uri
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Token
A valid Security token for a user/principal that has access to the Subscription

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ApiVersion
Version of the API for this request

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -DisableCertificateValidation
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

### -InformationAction
@{Text=}

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}

```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
@{Text=}

```yaml
Type: String
Parameter Sets: TenantGet
Aliases: 

Required: True
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: Admin
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroup
@{Text=}

```yaml
Type: String
Parameter Sets: Admin
Aliases: 

Required: True
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
The Id of the subscription that has access to the required namespace to complete the operation

```yaml
Type: Guid
Parameter Sets: Admin
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Managed
@{Text=}

```yaml
Type: SwitchParameter
Parameter Sets: Admin
Aliases: 

Required: True
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

