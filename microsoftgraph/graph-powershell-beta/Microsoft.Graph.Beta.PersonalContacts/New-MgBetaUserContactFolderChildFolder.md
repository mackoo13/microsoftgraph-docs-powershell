---
external help file: Microsoft.Graph.Beta.PersonalContacts-help.xml
Module Name: Microsoft.Graph.Beta.PersonalContacts
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.personalcontacts/new-mgbetausercontactextension
schema: 2.0.0
---

# New-MgBetaUserContactExtension

## SYNOPSIS
Create new navigation property to extensions for users

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [New-MgUserContactFolderChildFolder](/powershell/module/Microsoft.Graph.PersonalContacts/New-MgUserContactFolderChildFolder?view=graph-powershell-1.0)

## SYNTAX

### CreateExpanded (Default)
```
New-MgBetaUserContactExtension -ContactId <String> -UserId <String> [-AdditionalProperties <Hashtable>]
 [-Id <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgBetaUserContactExtension -ContactId <String> -UserId <String> -BodyParameter <Hashtable> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgBetaUserContactExtension -InputObject <IPersonalContactsIdentity> [-AdditionalProperties <Hashtable>]
 [-Id <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgBetaUserContactExtension -InputObject <IPersonalContactsIdentity> -BodyParameter <Hashtable> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to extensions for users

## EXAMPLES
### Example 1: Code snippet

```powershell
Import-Module Microsoft.Graph.Beta.PersonalContacts

$params = @{
	displayName = "Family"
}

# A UPN can also be used as -UserId.
New-MgBetaUserContactFolderChildFolder -UserId $userId -ContactFolderId $contactFolderId -BodyParameter $params
```
This example shows how to use the New-MgBetaUserContactFolderChildFolder Cmdlet.

To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).


## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
extension

```yaml
Type: Hashtable
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ContactId
The unique identifier of contact

```yaml
Type: String
Parameter Sets: CreateExpanded, Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The unique identifier for an entity.
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IPersonalContactsIdentity
Parameter Sets: CreateViaIdentityExpanded, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -UserId
The unique identifier of user

```yaml
Type: String
Parameter Sets: CreateExpanded, Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IPersonalContactsIdentity
### System.Collections.Hashtable
## OUTPUTS

### System.String
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`INPUTOBJECT <IPersonalContactsIdentity>`: Identity Parameter
  - `[ContactFolderId <String>]`: The unique identifier of contactFolder
  - `[ContactFolderId1 <String>]`: The unique identifier of contactFolder
  - `[ContactId <String>]`: The unique identifier of contact
  - `[ExtensionId <String>]`: The unique identifier of extension
  - `[UserId <String>]`: The unique identifier of user

## RELATED LINKS
[New-MgUserContactFolderChildFolder](/powershell/module/Microsoft.Graph.PersonalContacts/New-MgUserContactFolderChildFolder?view=graph-powershell-1.0)
