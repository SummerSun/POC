---
external help file: SMAzure_Compute.xml
online version: 4b060a7d-da50-45ff-adb6-bcba63faa90b
schema: 2.0.0
updated_at: 9/8/2016 10:40 AM
ms.date: 9/8/2016
ms.topic: reference
content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v1.0/Resume-WAPackVM.md
original_content_git_url: https://github.com/azure/azure-docs-powershell.git/blob/master/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v1.0/Resume-WAPackVM.md
gitcommit: https://github.com/azure/azure-docs-powershell.git/blob/8903b0f1daa01932ac5fa167f377736de2df6709/azureps-cmdlets-docs/Service%20Management/Compute%20Cmdlets/v1.0/Resume-WAPackVM.md
---

# Resume-WAPackVM
## SYNOPSIS
Resumes paused virtual machines.

## SYNTAX

```
Resume-WAPackVM [-VM] <VirtualMachine> [-PassThru]
```

## DESCRIPTION
These topics are deprecated and will be removed in the future.
For the updated topics, see  Azure WAPack Cmdletshttp://msdn.microsoft.com/library/dn776450.aspx.
This topic describes the cmdlet in the 0.8.1 version of the Microsoft Azure PowerShell module.
To find out the version of the module you're using, from the Azure PowerShell console, type (get-module azure).version.

The Resume-WAPackVM cmdlet resumes paused virtual machines.

## EXAMPLES

### Example 1: Resume a virtual machine
```
PS C:\>$VirtualMachine = Get-WAPackVM -Name "ContosoV126"PS C:\> Resume-WAPackVM -VM $VirtualMachine
```

The first command gets the virtual machine named ContosoV126 by using the Get-WAPackVM cmdlet, and then stores that object in the $VirtualMachine variable.

The second command resumes the virtual machine stored in $VirtualMachine.

## PARAMETERS

### -PassThru
Returns an object representing the item with which you are working.
By default, this cmdlet does not generate any output.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -VM
Specifies a virtual machine.
To obtain a virtual machine, use the Get-WAPackVM cmdlet.

```yaml
Type: VirtualMachine
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: 
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-WAPackVM](4b060a7d-da50-45ff-adb6-bcba63faa90b)

[New-WAPackVM](1f74deb4-e9b0-4aeb-8e13-b1554a4ebbec)

[Remove-WAPackVM](76b51795-43e6-45c3-ade1-aa8ea61efc23)

[Restart-WAPackVM](fd89742d-0d21-41e9-b3b1-5d8c638f8c6d)

[Set-WAPackVM](8b07e4cb-c677-4e6b-b034-25847da03dbf)

[Start-WAPackVM](8cc5bf6b-bf5b-427f-922d-57e4a99b2d55)

[Stop-WAPackVM](7f3e6c33-2196-4e24-95fd-e5763c6f7402)

[Suspend-WAPackVM](d8041113-5a71-447d-9bbe-dc6405aa6029)
