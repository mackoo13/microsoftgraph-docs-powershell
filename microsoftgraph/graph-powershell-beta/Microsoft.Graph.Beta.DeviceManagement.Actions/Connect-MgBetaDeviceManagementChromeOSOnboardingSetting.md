---
external help file: Microsoft.Graph.Beta.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.Beta.DeviceManagement.Actions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devicemanagement.actions/connect-mgbetadevicemanagementchromeosonboardingsetting
schema: 2.0.0
---

# Connect-MgBetaDeviceManagementChromeOSOnboardingSetting

## SYNOPSIS
Invoke action connect

## SYNTAX

### ConnectExpanded (Default)
```
Connect-MgBetaDeviceManagementChromeOSOnboardingSetting [-AdditionalProperties <Hashtable>]
 [-OwnerAccessToken <String>] [-OwnerUserPrincipalName <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Connect
```
Connect-MgBetaDeviceManagementChromeOSOnboardingSetting
 -Body <IPaths5LbknhDevicemanagementChromeosonboardingsettingsMicrosoftGraphConnectPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action connect

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: ConnectExpanded
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
Type: IPaths5LbknhDevicemanagementChromeosonboardingsettingsMicrosoftGraphConnectPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Connect
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OwnerAccessToken
.

```yaml
Type: String
Parameter Sets: ConnectExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OwnerUserPrincipalName
.

```yaml
Type: String
Parameter Sets: ConnectExpanded
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

### Microsoft.Graph.Beta.PowerShell.Models.IPaths5LbknhDevicemanagementChromeosonboardingsettingsMicrosoftGraphConnectPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Support.ChromeOSOnboardingStatus
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODY <IPaths5LbknhDevicemanagementChromeosonboardingsettingsMicrosoftGraphConnectPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[OwnerAccessToken <String>]`: 
  - `[OwnerUserPrincipalName <String>]`: 

## RELATED LINKS

