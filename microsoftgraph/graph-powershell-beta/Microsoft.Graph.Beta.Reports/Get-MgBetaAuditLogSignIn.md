---
external help file: Microsoft.Graph.Beta.Reports-help.xml
Module Name: Microsoft.Graph.Beta.Reports
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.reports/get-mgbetaauditlogsignin
schema: 2.0.0
ms.prod: identity-and-access-reports
ms.prod: identity-and-access-reports
---

# Get-MgBetaAuditLogSignIn

## SYNOPSIS
Get a signIn object that contains a specific user sign-in event for your tenant.
This includes sign-ins where a user is asked to enter a username or password, and session tokens.

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [Get-MgAuditLogSignIn](/powershell/module/Microsoft.Graph.Reports/Get-MgAuditLogSignIn?view=graph-powershell-1.0)

## SYNTAX

### List (Default)
```
Get-MgBetaAuditLogSignIn [-ExpandProperty <String[]>] [-Property <String[]>] [-Filter <String>]
 [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-PageSize <Int32>] [-All]
 [-CountVariable <String>] [<CommonParameters>]
```

### Get
```
Get-MgBetaAuditLogSignIn -SignInId <String> [-ExpandProperty <String[]>] [-Property <String[]>]
 [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgBetaAuditLogSignIn -InputObject <IReportsIdentity> [-ExpandProperty <String[]>] [-Property <String[]>]
 [<CommonParameters>]
```

## DESCRIPTION
Get a signIn object that contains a specific user sign-in event for your tenant.
This includes sign-ins where a user is asked to enter a username or password, and session tokens.

## EXAMPLES
### Example 1: List all sign-ins

```powershell

Import-Module Microsoft.Graph.Beta.Reports

Get-MgBetaAuditLogSignIn

```
This example will list all sign-ins

### Example 2: Retrieve the first 10 sign-ins to apps with the appDisplayName that starts with 'Azure'

```powershell

Import-Module Microsoft.Graph.Beta.Reports

Get-MgBetaAuditLogSignIn -Filter "startsWith(appDisplayName,'Azure')" -Top 10 

```
This example will retrieve the first 10 sign-ins to apps with the appdisplayname that starts with 'azure'

### Example 3: Retrieve the first 10 sign-ins where the signInEventType is not interactiveUser starting with the latest sign-in

```powershell

Import-Module Microsoft.Graph.Beta.Reports

Get-MgBetaAuditLogSignIn -Filter "(signInEventTypes/any(t: t ne 'interactiveUser'))" -Sort "createdDateTime DESC" -Top 10 

```
This example will retrieve the first 10 sign-ins where the signineventtype is not interactiveuser starting with the latest sign-in


## PARAMETERS

### -All
List all pages.

```yaml
Type: SwitchParameter
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CountVariable
Specifies a count of the total number of items in a collection.
By default, this variable will be set in the global scope.

```yaml
Type: String
Parameter Sets: List
Aliases: CV

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpandProperty
Expand related entities

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Expand

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Filter
Filter items by property values

```yaml
Type: String
Parameter Sets: List
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
Type: IReportsIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PageSize
Sets the page size of results.

```yaml
Type: Int32
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Property
Select properties to be returned

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Select

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Search
Search items by search phrases

```yaml
Type: String
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SignInId
The unique identifier of signIn

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

### -Sort
Order items by property values

```yaml
Type: String[]
Parameter Sets: List
Aliases: OrderBy

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
Show only the first n items

```yaml
Type: Int32
Parameter Sets: List
Aliases: Limit

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Skip
Skip the first n items

```yaml
Type: Int32
Parameter Sets: List
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

### Microsoft.Graph.Beta.PowerShell.Models.IReportsIdentity
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphSignIn
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
[Get-MgAuditLogSignIn](/powershell/module/Microsoft.Graph.Reports/Get-MgAuditLogSignIn?view=graph-powershell-1.0)
