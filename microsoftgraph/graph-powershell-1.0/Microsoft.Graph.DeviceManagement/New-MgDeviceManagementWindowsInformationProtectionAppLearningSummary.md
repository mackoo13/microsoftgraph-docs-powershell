---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.devicemanagement/new-mgdevicemanagementwindowsinformationprotectionapplearningsummary
schema: 2.0.0
---

# New-MgDeviceManagementWindowsInformationProtectionAppLearningSummary

## SYNOPSIS
Create a new windowsInformationProtectionAppLearningSummary object.

> [!NOTE]
> To view the beta release of this cmdlet, view [New-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary](/powershell/module/Microsoft.Graph.Beta.DeviceManagement/New-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary?view=graph-powershell-beta)

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceManagementWindowsInformationProtectionAppLearningSummary [-AdditionalProperties <Hashtable>]
 [-ApplicationName <String>] [-ApplicationType <ApplicationType>] [-DeviceCount <Int32>] [-Id <String>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDeviceManagementWindowsInformationProtectionAppLearningSummary
 -BodyParameter <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Create a new windowsInformationProtectionAppLearningSummary object.

## PARAMETERS

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

### -ApplicationName
Application Name

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

### -ApplicationType
Possible types of Application

```yaml
Type: ApplicationType
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Windows Information Protection AppLearning Summary entity.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsInformationProtectionAppLearningSummary
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeviceCount
Device Count

```yaml
Type: Int32
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionAppLearningSummary
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionAppLearningSummary
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary>`: Windows Information Protection AppLearning Summary entity.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[ApplicationName <String>]`: Application Name
  - `[ApplicationType <ApplicationType?>]`: Possible types of Application
  - `[DeviceCount <Int32?>]`: Device Count

## RELATED LINKS
[New-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary](/powershell/module/Microsoft.Graph.Beta.DeviceManagement/New-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary?view=graph-powershell-beta)

