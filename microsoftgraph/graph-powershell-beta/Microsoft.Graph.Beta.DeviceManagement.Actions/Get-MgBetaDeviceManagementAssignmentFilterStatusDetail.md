---
external help file: Microsoft.Graph.Beta.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.Beta.DeviceManagement.Actions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devicemanagement.actions/get-mgbetadevicemanagementassignmentfilterstatusdetail
schema: 2.0.0
---

# Get-MgBetaDeviceManagementAssignmentFilterStatusDetail

## SYNOPSIS
Invoke action getAssignmentFiltersStatusDetails

## SYNTAX

### GetExpanded (Default)
```
Get-MgBetaDeviceManagementAssignmentFilterStatusDetail [-AdditionalProperties <Hashtable>]
 [-AssignmentFilterIds <String[]>] [-ManagedDeviceId <String>] [-PayloadId <String>] [-Skip <Int32>]
 [-Top <Int32>] [-UserId <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Get
```
Get-MgBetaDeviceManagementAssignmentFilterStatusDetail
 -BodyParameter <IPaths1Dv3M96DevicemanagementMicrosoftGraphGetassignmentfiltersstatusdetailsPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action getAssignmentFiltersStatusDetails

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: GetExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AssignmentFilterIds
.

```yaml
Type: String[]
Parameter Sets: GetExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IPaths1Dv3M96DevicemanagementMicrosoftGraphGetassignmentfiltersstatusdetailsPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ManagedDeviceId
.

```yaml
Type: String
Parameter Sets: GetExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PayloadId
.

```yaml
Type: String
Parameter Sets: GetExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
.

```yaml
Type: Int32
Parameter Sets: GetExpanded
Aliases: Limit

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
.

```yaml
Type: String
Parameter Sets: GetExpanded
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

### -Skip
.

```yaml
Type: Int32
Parameter Sets: GetExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IPaths1Dv3M96DevicemanagementMicrosoftGraphGetassignmentfiltersstatusdetailsPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphAssignmentFilterStatusDetails
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IPaths1Dv3M96DevicemanagementMicrosoftGraphGetassignmentfiltersstatusdetailsPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AssignmentFilterIds <String[]>]`: 
  - `[ManagedDeviceId <String>]`: 
  - `[PayloadId <String>]`: 
  - `[Skip <Int32?>]`: 
  - `[Top <Int32?>]`: 
  - `[UserId <String>]`: 

## RELATED LINKS

