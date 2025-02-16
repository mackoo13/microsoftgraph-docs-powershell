---
external help file: Microsoft.Graph.Beta.Reports-help.xml
Module Name: Microsoft.Graph.Beta.Reports
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.reports/invoke-mgbetagraphreportauthenticationmethod
schema: 2.0.0
---

# Invoke-MgBetaGraphReportAuthenticationMethod

## SYNOPSIS
Invoke function usersRegisteredByFeature

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [Invoke-MgGraphReportAuthenticationMethod](/powershell/module/Microsoft.Graph.Reports/Invoke-MgGraphReportAuthenticationMethod?view=graph-powershell-1.0)

## SYNTAX

### Graph (Default)
```
Invoke-MgBetaGraphReportAuthenticationMethod [<CommonParameters>]
```

### Graph3
```
Invoke-MgBetaGraphReportAuthenticationMethod -IncludedUserRoles <String> -IncludedUserTypes <String>
 [<CommonParameters>]
```

### Graph1
```
Invoke-MgBetaGraphReportAuthenticationMethod -IncludedUserRoles <String> -IncludedUserTypes <String>
 [<CommonParameters>]
```

### GraphViaIdentity1
```
Invoke-MgBetaGraphReportAuthenticationMethod -InputObject <IReportsIdentity> [<CommonParameters>]
```

### GraphViaIdentity
```
Invoke-MgBetaGraphReportAuthenticationMethod -InputObject <IReportsIdentity> [<CommonParameters>]
```

## DESCRIPTION
Invoke function usersRegisteredByFeature

## PARAMETERS

### -IncludedUserRoles
Usage: includedUserRoles='{includedUserRoles}'

```yaml
Type: String
Parameter Sets: Graph3, Graph1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IncludedUserTypes
Usage: includedUserTypes='{includedUserTypes}'

```yaml
Type: String
Parameter Sets: Graph3, Graph1
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
Type: IReportsIdentity
Parameter Sets: GraphViaIdentity1, GraphViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IReportsIdentity
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphUserRegistrationFeatureSummary
### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphUserRegistrationMethodSummary
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`INPUTOBJECT <IReportsIdentity>`: Identity Parameter
  - `[AppCredentialSignInActivityId <String>]`: The unique identifier of appCredentialSignInActivity
  - `[ApplicationSignInDetailedSummaryId <String>]`: The unique identifier of applicationSignInDetailedSummary
  - `[CredentialUserRegistrationDetailsId <String>]`: The unique identifier of credentialUserRegistrationDetails
  - `[CustomSecurityAttributeAuditId <String>]`: The unique identifier of customSecurityAttributeAudit
  - `[Date <DateTime?>]`: Usage: date={date}
  - `[DeviceManagementCachedReportConfigurationId <String>]`: The unique identifier of deviceManagementCachedReportConfiguration
  - `[DeviceManagementExportJobId <String>]`: The unique identifier of deviceManagementExportJob
  - `[DirectoryAuditId <String>]`: The unique identifier of directoryAudit
  - `[EndDateTime <DateTime?>]`: Usage: endDateTime={endDateTime}
  - `[Filter <String>]`: Usage: filter='{filter}'
  - `[GroupId <String>]`: Usage: groupId='{groupId}'
  - `[IncludedUserRoles <String>]`: Usage: includedUserRoles='{includedUserRoles}'
  - `[IncludedUserTypes <String>]`: Usage: includedUserTypes='{includedUserTypes}'
  - `[Period <String>]`: Usage: period='{period}'
  - `[PrintUsageByPrinterId <String>]`: The unique identifier of printUsageByPrinter
  - `[PrintUsageByUserId <String>]`: The unique identifier of printUsageByUser
  - `[PrintUsageId <String>]`: The unique identifier of printUsage
  - `[PrinterId <String>]`: Usage: printerId='{printerId}'
  - `[ProvisioningObjectSummaryId <String>]`: The unique identifier of provisioningObjectSummary
  - `[ServicePrincipalSignInActivityId <String>]`: The unique identifier of servicePrincipalSignInActivity
  - `[SignInId <String>]`: The unique identifier of signIn
  - `[Skip <Int32?>]`: Usage: skip={skip}
  - `[SkipToken <String>]`: Usage: skipToken='{skipToken}'
  - `[StartDateTime <DateTime?>]`: Usage: startDateTime={startDateTime}
  - `[Top <Int32?>]`: Usage: top={top}
  - `[UserCredentialUsageDetailsId <String>]`: The unique identifier of userCredentialUsageDetails
  - `[UserId <String>]`: Usage: userId='{userId}'
  - `[UserRegistrationDetailsId <String>]`: The unique identifier of userRegistrationDetails

## RELATED LINKS
[Invoke-MgGraphReportAuthenticationMethod](/powershell/module/Microsoft.Graph.Reports/Invoke-MgGraphReportAuthenticationMethod?view=graph-powershell-1.0)

