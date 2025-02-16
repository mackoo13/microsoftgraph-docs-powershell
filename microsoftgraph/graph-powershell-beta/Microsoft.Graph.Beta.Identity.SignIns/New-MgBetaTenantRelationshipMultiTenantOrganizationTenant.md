---
external help file: Microsoft.Graph.Beta.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Beta.Identity.SignIns
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.identity.signins/new-mgbetatenantrelationshipmultitenantorganizationtenant
schema: 2.0.0
---

# New-MgBetaTenantRelationshipMultiTenantOrganizationTenant

## SYNOPSIS
Add a tenant to a multi-tenant organization.
The administrator of an owner tenant has the permissions to add tenants to the multi-tenant organization.
The added tenant is in the pending state until the administrator of the added tenant joins the multi-tenant organization by submitting a join request.
Note that a tenant can be part of only one multi-tenant organization.

## SYNTAX

### CreateExpanded (Default)
```
New-MgBetaTenantRelationshipMultiTenantOrganizationTenant [-AddedByTenantId <String>]
 [-AddedDateTime <DateTime>] [-AdditionalProperties <Hashtable>] [-DeletedDateTime <DateTime>]
 [-DisplayName <String>] [-Id <String>] [-JoinedDateTime <DateTime>] [-Role <String>] [-State <String>]
 [-TenantId <String>] [-TransitionDetails <IMicrosoftGraphMultiTenantOrganizationMemberTransitionDetails>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgBetaTenantRelationshipMultiTenantOrganizationTenant
 -BodyParameter <IMicrosoftGraphMultiTenantOrganizationMember> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Add a tenant to a multi-tenant organization.
The administrator of an owner tenant has the permissions to add tenants to the multi-tenant organization.
The added tenant is in the pending state until the administrator of the added tenant joins the multi-tenant organization by submitting a join request.
Note that a tenant can be part of only one multi-tenant organization.

## PARAMETERS

### -AddedByTenantId
Tenant ID of the tenant that added the tenant to the multi-tenant organization.
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AddedDateTime
Date and time when the tenant was added to the multi-tenant organization.
Read-only.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
multiTenantOrganizationMember
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphMultiTenantOrganizationMember
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeletedDateTime
Date and time when this object was deleted.
Always null when the object hasn't been deleted.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Display name of the tenant added to the multi-tenant organization.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -JoinedDateTime
Date and time when the tenant joined the multi-tenant organization.
Read-only.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Role
multiTenantOrganizationMemberRole

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
multiTenantOrganizationMemberState

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TenantId
Tenant ID of the Azure Active Directory tenant added to the multi-tenant organization.
Set at the time tenant is added.Supports $filter.
Key.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TransitionDetails
multiTenantOrganizationMemberTransitionDetails
To construct, see NOTES section for TRANSITIONDETAILS properties and create a hash table.

```yaml
Type: IMicrosoftGraphMultiTenantOrganizationMemberTransitionDetails
Parameter Sets: CreateExpanded
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

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphMultiTenantOrganizationMember
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphMultiTenantOrganizationMember
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IMicrosoftGraphMultiTenantOrganizationMember>`: multiTenantOrganizationMember
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DeletedDateTime <DateTime?>]`: Date and time when this object was deleted. Always null when the object hasn't been deleted.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[AddedByTenantId <String>]`: Tenant ID of the tenant that added the tenant to the multi-tenant organization. Read-only.
  - `[AddedDateTime <DateTime?>]`: Date and time when the tenant was added to the multi-tenant organization. Read-only.
  - `[DisplayName <String>]`: Display name of the tenant added to the multi-tenant organization.
  - `[JoinedDateTime <DateTime?>]`: Date and time when the tenant joined the multi-tenant organization. Read-only.
  - `[Role <String>]`: multiTenantOrganizationMemberRole
  - `[State <String>]`: multiTenantOrganizationMemberState
  - `[TenantId <String>]`: Tenant ID of the Azure Active Directory tenant added to the multi-tenant organization. Set at the time tenant is added.Supports $filter. Key.
  - `[TransitionDetails <IMicrosoftGraphMultiTenantOrganizationMemberTransitionDetails>]`: multiTenantOrganizationMemberTransitionDetails
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DesiredRole <String>]`: multiTenantOrganizationMemberRole
    - `[DesiredState <String>]`: multiTenantOrganizationMemberState
    - `[Details <String>]`: Details that explain the processing status if any. Read-only.
    - `[Status <String>]`: multiTenantOrganizationMemberProcessingStatus

`TRANSITIONDETAILS <IMicrosoftGraphMultiTenantOrganizationMemberTransitionDetails>`: multiTenantOrganizationMemberTransitionDetails
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DesiredRole <String>]`: multiTenantOrganizationMemberRole
  - `[DesiredState <String>]`: multiTenantOrganizationMemberState
  - `[Details <String>]`: Details that explain the processing status if any. Read-only.
  - `[Status <String>]`: multiTenantOrganizationMemberProcessingStatus

## RELATED LINKS

