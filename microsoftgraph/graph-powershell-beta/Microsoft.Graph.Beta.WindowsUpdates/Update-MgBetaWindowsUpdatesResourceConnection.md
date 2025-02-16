---
external help file: Microsoft.Graph.Beta.WindowsUpdates-help.xml
Module Name: Microsoft.Graph.Beta.WindowsUpdates
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.windowsupdates/update-mgbetawindowsupdatesresourceconnection
schema: 2.0.0
---

# Update-MgBetaWindowsUpdatesResourceConnection

## SYNOPSIS
Update the navigation property resourceConnections in admin

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgBetaWindowsUpdatesResourceConnection -ResourceConnectionId <String>
 [-AdditionalProperties <Hashtable>] [-Id <String>] [-State <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgBetaWindowsUpdatesResourceConnection -ResourceConnectionId <String>
 -BodyParameter <IMicrosoftGraphWindowsUpdatesResourceConnection> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgBetaWindowsUpdatesResourceConnection -InputObject <IWindowsUpdatesIdentity>
 [-AdditionalProperties <Hashtable>] [-Id <String>] [-State <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgBetaWindowsUpdatesResourceConnection -InputObject <IWindowsUpdatesIdentity>
 -BodyParameter <IMicrosoftGraphWindowsUpdatesResourceConnection> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property resourceConnections in admin

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
resourceConnection
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsUpdatesResourceConnection
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Id
The unique identifier for an entity.
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Type: IWindowsUpdatesIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ResourceConnectionId
The unique identifier of resourceConnection

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
resourceConnectionState

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
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

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphWindowsUpdatesResourceConnection
### Microsoft.Graph.Beta.PowerShell.Models.IWindowsUpdatesIdentity
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphWindowsUpdatesResourceConnection
## NOTES

ALIASES

Update-MgBetaWuResourceConnection

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IMicrosoftGraphWindowsUpdatesResourceConnection>`: resourceConnection
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[State <String>]`: resourceConnectionState

`INPUTOBJECT <IWindowsUpdatesIdentity>`: Identity Parameter
  - `[CatalogEntryId <String>]`: The unique identifier of catalogEntry
  - `[ComplianceChangeId <String>]`: The unique identifier of complianceChange
  - `[DeploymentId <String>]`: The unique identifier of deployment
  - `[ResourceConnectionId <String>]`: The unique identifier of resourceConnection
  - `[UpdatableAssetId <String>]`: The unique identifier of updatableAsset
  - `[UpdatePolicyId <String>]`: The unique identifier of updatePolicy

## RELATED LINKS

