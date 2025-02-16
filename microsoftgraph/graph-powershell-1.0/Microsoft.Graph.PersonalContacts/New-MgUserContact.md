---
external help file: Microsoft.Graph.PersonalContacts-help.xml
Module Name: Microsoft.Graph.PersonalContacts
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.personalcontacts/get-mgusercontactphotocontent
schema: 2.0.0
---

# Get-MgUserContactPhotoContent

## SYNOPSIS
Get media content for the navigation property photo from users

> [!NOTE]
> To view the beta release of this cmdlet, view [New-MgBetaUserContact](/powershell/module/Microsoft.Graph.Beta.PersonalContacts/New-MgBetaUserContact?view=graph-powershell-beta)

## SYNTAX

### Get (Default)
```
Get-MgUserContactPhotoContent -ContactId <String> -UserId <String> -OutFile <String> [-PassThru]
 [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgUserContactPhotoContent -InputObject <IPersonalContactsIdentity> -OutFile <String> [-PassThru]
 [<CommonParameters>]
```

## DESCRIPTION
Get media content for the navigation property photo from users

## EXAMPLES
### Example 1: Code snippet

```powershell
Import-Module Microsoft.Graph.PersonalContacts

$params = @{
	givenName = "Pavel"
	surname = "Bansky"
	emailAddresses = @(
		@{
			address = "pavelb@fabrikam.onmicrosoft.com"
			name = "Pavel Bansky"
		}
	)
	businessPhones = @(
		"+1 732 555 0102"
	)
}

# A UPN can also be used as -UserId.
New-MgUserContact -UserId $userId -BodyParameter $params
```
This example shows how to use the New-MgUserContact Cmdlet.

To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).


## PARAMETERS

### -ContactId
The unique identifier of contact

```yaml
Type: String
Parameter Sets: Get
Aliases:

Required: True
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
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OutFile
Path to write output file to

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
The unique identifier of user

```yaml
Type: String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IPersonalContactsIdentity
## OUTPUTS

### System.Boolean
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
[New-MgBetaUserContact](/powershell/module/Microsoft.Graph.Beta.PersonalContacts/New-MgBetaUserContact?view=graph-powershell-beta)
