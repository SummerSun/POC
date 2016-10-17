---
external help file: Microsoft.WindowsAzure.Commands.SqlDatabase.dll-Help.xml
online version: https://azure.microsoft.com/en-us/services/sql-database/
schema: 2.0.0
updated_at: 10/15/2016 4:32 AM
ms.date: 10/15/2016
content_git_url: https://github.com/SummerSun/azure-docs-powershell-int/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.SQLDatabase/v1.0/CmdletMDs/Get-AzureSqlDatabaseServerFirewallRule.md
gitcommit: https://github.com/SummerSun/azure-docs-powershell-int/blob/1bfd8e268acfc1799ad3f17c5a982578f54443cf/azureps-cmdlets-docs/ServiceManagement/Azure.SQLDatabase/v1.0/CmdletMDs/Get-AzureSqlDatabaseServerFirewallRule.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Get-AzureSqlDatabaseServerFirewallRule

## SYNOPSIS
Gets firewall rules for ssSDS Server.

## SYNTAX

```
Get-AzureSqlDatabaseServerFirewallRule [-ServerName] <String> [-RuleName <String>] [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureSqlDatabaseServerFirewallRule** cmdlet gets firewall rules for an instance of ssSDS Server.
If you specify a firewall rule by name, this cmdlet returns information about that firewall rule.
Otherwise, the cmdlet returns information about all the firewall rules on the specified ssSDS server.

## EXAMPLES

### Example 1: Get all firewall rules on a server
```
PS C:\>Get-AzureSqlDatabaseServerFirewallRule -ServerName "lpqd0zbr8y"
```

This command gets all the firewall rules on the ssSDS server named lpqd0zbr8y.

### Example 2: Get a firewall rule by using its name
```
PS C:\>Get-AzureSqlDatabaseServerFirewallRule -ServerName "lpqd0zbr8y" -RuleName "FirewallRule24"
```

This command gets the firewall rule named FirewallRule24 on the server named lpqd0zbr8y.

## PARAMETERS

### -ServerName
Specifies the name of a server.
This cmdlet gets firewall rules from the server that this parameter specifies.
Specify the server name, not the fully qualified DNS name.

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

### -RuleName
Specifies the name of the firewall rule that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
ps_azureprofile_description

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

### Microsoft.WindowsAzure.Commands.SqlDatabase.Model.SqlDatabaseServerFirewallRuleContext

## OUTPUTS

### IEnumerable<Microsoft.WindowsAzure.Commands.SqlDatabase.Model.SqlDatabaseServerFirewallRuleContext>

## NOTES

## RELATED LINKS

[Azure SQL Database](https://azure.microsoft.com/en-us/services/sql-database/)

[List Firewall Rules](https://msdn.microsoft.com/en-us/library/azure/dn505715.aspx)

[Operations for Azure SQL Databases](https://msdn.microsoft.com/en-us/library/azure/dn505719.aspx)

[New-AzureSqlDatabaseServerFirewallRule](.\New-AzureSqlDatabaseServerFirewallRule.md)

[Remove-AzureSqlDatabaseServerFirewallRule](.\Remove-AzureSqlDatabaseServerFirewallRule.md)

[Set-AzureSqlDatabaseServerFirewallRule](.\Set-AzureSqlDatabaseServerFirewallRule.md)

