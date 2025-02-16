---
external help file: Microsoft.Graph.Beta.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.Beta.DeviceManagement.Actions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devicemanagement.actions/invoke-mgbetahasdevicemanagementdeviceenrollmentconfigurationpayloadlink
schema: 2.0.0
---

# Invoke-MgBetaHasDeviceManagementDeviceEnrollmentConfigurationPayloadLink

## SYNOPSIS
Invoke action hasPayloadLinks

## SYNTAX

### LinkExpanded (Default)
```
Invoke-MgBetaHasDeviceManagementDeviceEnrollmentConfigurationPayloadLink [-AdditionalProperties <Hashtable>]
 [-PayloadIds <String[]>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Link
```
Invoke-MgBetaHasDeviceManagementDeviceEnrollmentConfigurationPayloadLink
 -Body <IPaths1Uvh7JwDevicemanagementDeviceenrollmentconfigurationsMicrosoftGraphHaspayloadlinksPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action hasPayloadLinks

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: LinkExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Body
.
To construct, see NOTES section for BODY properties and create a hash table.

```yaml
Type: IPaths1Uvh7JwDevicemanagementDeviceenrollmentconfigurationsMicrosoftGraphHaspayloadlinksPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Link
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PayloadIds
.

```yaml
Type: String[]
Parameter Sets: LinkExpanded
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

### Microsoft.Graph.Beta.PowerShell.Models.IPaths1Uvh7JwDevicemanagementDeviceenrollmentconfigurationsMicrosoftGraphHaspayloadlinksPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphHasPayloadLinkResultItem
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODY <IPaths1Uvh7JwDevicemanagementDeviceenrollmentconfigurationsMicrosoftGraphHaspayloadlinksPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[PayloadIds <String[]>]`: 

## RELATED LINKS

