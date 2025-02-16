---
external help file: Microsoft.Graph.Beta.Applications-help.xml
Module Name: Microsoft.Graph.Beta.Applications
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.applications/new-mgbetaserviceprincipalsynchronizationjobondemand
schema: 2.0.0
---

# New-MgBetaServicePrincipalSynchronizationJobOnDemand

## SYNOPSIS
Select a user and provision the account on-demand.
The rate limit for this API is 5 requests per 10 seconds.
No user or group will be provisioned on-demand that would not have been provisioned through the regular provisioning cycles.

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [New-MgServicePrincipalSynchronizationJobOnDemand](/powershell/module/Microsoft.Graph.Applications/New-MgServicePrincipalSynchronizationJobOnDemand?view=graph-powershell-1.0)

## SYNTAX

### ProvisionExpanded (Default)
```
New-MgBetaServicePrincipalSynchronizationJobOnDemand -ServicePrincipalId <String>
 -SynchronizationJobId <String> [-AdditionalProperties <Hashtable>]
 [-Parameters <IMicrosoftGraphSynchronizationJobApplicationParameters[]>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Provision
```
New-MgBetaServicePrincipalSynchronizationJobOnDemand -ServicePrincipalId <String>
 -SynchronizationJobId <String>
 -BodyParameter <IPathsJgtujvServiceprincipalsServiceprincipalIdSynchronizationJobsSynchronizationjobIdMicrosoftGraphProvisionondemandPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ProvisionViaIdentityExpanded
```
New-MgBetaServicePrincipalSynchronizationJobOnDemand -InputObject <IApplicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-Parameters <IMicrosoftGraphSynchronizationJobApplicationParameters[]>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ProvisionViaIdentity
```
New-MgBetaServicePrincipalSynchronizationJobOnDemand -InputObject <IApplicationsIdentity>
 -BodyParameter <IPathsJgtujvServiceprincipalsServiceprincipalIdSynchronizationJobsSynchronizationjobIdMicrosoftGraphProvisionondemandPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Select a user and provision the account on-demand.
The rate limit for this API is 5 requests per 10 seconds.
No user or group will be provisioned on-demand that would not have been provisioned through the regular provisioning cycles.

## EXAMPLES
### Example 1: Using the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet
```powershell
Import-Module Microsoft.Graph.Beta.Applications
$params = @{
	Parameters = @(
		@{
			RuleId = "6c409270-f78a-4bc6-af23-7cf3ab6482fe"
			Subjects = @(
				@{
					ObjectId = "CN=AdeleV,CN=Users,DC=corp,DC=chicago,DC=com"
					ObjectTypeName = "user"
				}
			)
		}
	)
}
New-MgBetaServicePrincipalSynchronizationJobOnDemand -ServicePrincipalId $servicePrincipalId -SynchronizationJobId $synchronizationJobId -BodyParameter $params
```
This example shows how to use the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).
### Example 2: Using the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet
```powershell
Import-Module Microsoft.Graph.Beta.Applications
$params = @{
	Parameters = @(
		@{
			Subjects = @(
				@{
					ObjectId = "9bb0f679-a883-4a6f-8260-35b491b8b8c8"
					ObjectTypeName = "User"
				}
			)
			RuleId = "ea807875-5618-4f0a-9125-0b46a05298ca"
		}
	)
}
New-MgBetaServicePrincipalSynchronizationJobOnDemand -ServicePrincipalId $servicePrincipalId -SynchronizationJobId $synchronizationJobId -BodyParameter $params
```
This example shows how to use the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).
### Example 3: Using the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet
```powershell
Import-Module Microsoft.Graph.Beta.Applications
$params = @{
	Parameters = @(
		@{
			RuleId = "33f7c90d-bf71-41b1-bda6-aaf0ddbee5d8#V2"
			Subjects = @(
				@{
					ObjectId = "8213fd99-d6b6-417b-8e13-af6334856215"
					ObjectTypeName = "Group"
					Links = @{
						Members = @(
							@{
								ObjectId = "cbc86211-6ada-4803-b73f-8039cf56d8a2"
								ObjectTypeName = "User"
							}
							@{
								ObjectId = "2bc86211-6ada-4803-b73f-8039cf56d8a2"
								ObjectTypeName = "User"
							}
						)
					}
				}
			)
		}
	)
}
New-MgBetaServicePrincipalSynchronizationJobOnDemand -ServicePrincipalId $servicePrincipalId -SynchronizationJobId $synchronizationJobId -BodyParameter $params
```
This example shows how to use the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).
### Example 4: Using the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet
```powershell
Import-Module Microsoft.Graph.Beta.Applications
$params = @{
	Parameters = @(
		@{
			Subjects = @(
				@{
					ObjectId = "9bb0f679-a883-4a6f-8260-35b491b8b8c8"
					ObjectTypeName = "User"
				}
			)
			RuleId = "ea807875-5618-4f0a-9125-0b46a05298ca"
		}
	)
}
New-MgBetaServicePrincipalSynchronizationJobOnDemand -ServicePrincipalId $servicePrincipalId -SynchronizationJobId $synchronizationJobId -BodyParameter $params
```
This example shows how to use the New-MgBetaServicePrincipalSynchronizationJobOnDemand Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: ProvisionExpanded, ProvisionViaIdentityExpanded
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
Type: IPathsJgtujvServiceprincipalsServiceprincipalIdSynchronizationJobsSynchronizationjobIdMicrosoftGraphProvisionondemandPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Provision, ProvisionViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IApplicationsIdentity
Parameter Sets: ProvisionViaIdentityExpanded, ProvisionViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Parameters
.
To construct, see NOTES section for PARAMETERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphSynchronizationJobApplicationParameters[]
Parameter Sets: ProvisionExpanded, ProvisionViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServicePrincipalId
The unique identifier of servicePrincipal

```yaml
Type: String
Parameter Sets: ProvisionExpanded, Provision
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SynchronizationJobId
The unique identifier of synchronizationJob

```yaml
Type: String
Parameter Sets: ProvisionExpanded, Provision
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

### Microsoft.Graph.Beta.PowerShell.Models.IApplicationsIdentity
### Microsoft.Graph.Beta.PowerShell.Models.IPathsJgtujvServiceprincipalsServiceprincipalIdSynchronizationJobsSynchronizationjobIdMicrosoftGraphProvisionondemandPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphStringKeyStringValuePair
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IPathsJgtujvServiceprincipalsServiceprincipalIdSynchronizationJobsSynchronizationjobIdMicrosoftGraphProvisionondemandPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Parameters <IMicrosoftGraphSynchronizationJobApplicationParameters[]>]`: 
    - `[RuleId <String>]`: The identifier of the synchronizationRule to be applied. This rule ID is defined in the schema for a given synchronization job or template.
    - `[Subjects <IMicrosoftGraphSynchronizationJobSubject[]>]`: The identifiers of one or more objects to which a synchronizationJob is to be applied.
      - `[Links <IMicrosoftGraphSynchronizationLinkedObjects>]`: synchronizationLinkedObjects
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Manager <IMicrosoftGraphSynchronizationJobSubject>]`: synchronizationJobSubject
        - `[Members <IMicrosoftGraphSynchronizationJobSubject[]>]`: All group members that you would like to provision.
        - `[Owners <IMicrosoftGraphSynchronizationJobSubject[]>]`: 
      - `[ObjectId <String>]`: The identifier of an object to which a synchronizationJob is to be applied. Can be one of the following: An onPremisesDistinguishedName for synchronization from Active Directory to Azure AD.The user ID for synchronization from Azure AD to a third-party.The Worker ID of the Workday worker for synchronization from Workday to either Active Directory or Azure AD.
      - `[ObjectTypeName <String>]`: The type of the object to which a synchronizationJob is to be applied. Can be one of the following: user for synchronizing between Active Directory and Azure AD.User for synchronizing a user between Azure AD and a third-party application. Worker for synchronization a user between Workday and either Active Directory or Azure AD.Group for synchronizing a group between Azure AD and a third-party application.

`INPUTOBJECT <IApplicationsIdentity>`: Identity Parameter
  - `[AppId <String>]`: Alternate key of application
  - `[AppManagementPolicyId <String>]`: The unique identifier of appManagementPolicy
  - `[AppRoleAssignmentId <String>]`: The unique identifier of appRoleAssignment
  - `[ApplicationId <String>]`: The unique identifier of application
  - `[ApplicationTemplateId <String>]`: The unique identifier of applicationTemplate
  - `[ClaimsMappingPolicyId <String>]`: The unique identifier of claimsMappingPolicy
  - `[ConnectorGroupId <String>]`: The unique identifier of connectorGroup
  - `[ConnectorId <String>]`: The unique identifier of connector
  - `[DelegatedPermissionClassificationId <String>]`: The unique identifier of delegatedPermissionClassification
  - `[DirectoryDefinitionId <String>]`: The unique identifier of directoryDefinition
  - `[DirectoryObjectId <String>]`: The unique identifier of directoryObject
  - `[EndpointId <String>]`: The unique identifier of endpoint
  - `[ExtensionPropertyId <String>]`: The unique identifier of extensionProperty
  - `[FederatedIdentityCredentialId <String>]`: The unique identifier of federatedIdentityCredential
  - `[GroupId <String>]`: The unique identifier of group
  - `[HomeRealmDiscoveryPolicyId <String>]`: The unique identifier of homeRealmDiscoveryPolicy
  - `[LicenseDetailsId <String>]`: The unique identifier of licenseDetails
  - `[OAuth2PermissionGrantId <String>]`: The unique identifier of oAuth2PermissionGrant
  - `[OnPremisesAgentGroupId <String>]`: The unique identifier of onPremisesAgentGroup
  - `[OnPremisesAgentGroupId1 <String>]`: The unique identifier of onPremisesAgentGroup
  - `[OnPremisesAgentId <String>]`: The unique identifier of onPremisesAgent
  - `[OnPremisesPublishingProfileId <String>]`: The unique identifier of onPremisesPublishingProfile
  - `[PublishedResourceId <String>]`: The unique identifier of publishedResource
  - `[ServicePrincipalId <String>]`: The unique identifier of servicePrincipal
  - `[SynchronizationJobId <String>]`: The unique identifier of synchronizationJob
  - `[SynchronizationTemplateId <String>]`: The unique identifier of synchronizationTemplate
  - `[TokenIssuancePolicyId <String>]`: The unique identifier of tokenIssuancePolicy
  - `[TokenLifetimePolicyId <String>]`: The unique identifier of tokenLifetimePolicy
  - `[UniqueName <String>]`: Alternate key of application
  - `[UserId <String>]`: The unique identifier of user

`PARAMETERS <IMicrosoftGraphSynchronizationJobApplicationParameters[]>`: .
  - `[RuleId <String>]`: The identifier of the synchronizationRule to be applied. This rule ID is defined in the schema for a given synchronization job or template.
  - `[Subjects <IMicrosoftGraphSynchronizationJobSubject[]>]`: The identifiers of one or more objects to which a synchronizationJob is to be applied.
    - `[Links <IMicrosoftGraphSynchronizationLinkedObjects>]`: synchronizationLinkedObjects
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Manager <IMicrosoftGraphSynchronizationJobSubject>]`: synchronizationJobSubject
      - `[Members <IMicrosoftGraphSynchronizationJobSubject[]>]`: All group members that you would like to provision.
      - `[Owners <IMicrosoftGraphSynchronizationJobSubject[]>]`: 
    - `[ObjectId <String>]`: The identifier of an object to which a synchronizationJob is to be applied. Can be one of the following: An onPremisesDistinguishedName for synchronization from Active Directory to Azure AD.The user ID for synchronization from Azure AD to a third-party.The Worker ID of the Workday worker for synchronization from Workday to either Active Directory or Azure AD.
    - `[ObjectTypeName <String>]`: The type of the object to which a synchronizationJob is to be applied. Can be one of the following: user for synchronizing between Active Directory and Azure AD.User for synchronizing a user between Azure AD and a third-party application. Worker for synchronization a user between Workday and either Active Directory or Azure AD.Group for synchronizing a group between Azure AD and a third-party application.

## RELATED LINKS
[New-MgServicePrincipalSynchronizationJobOnDemand](/powershell/module/Microsoft.Graph.Applications/New-MgServicePrincipalSynchronizationJobOnDemand?view=graph-powershell-1.0)
