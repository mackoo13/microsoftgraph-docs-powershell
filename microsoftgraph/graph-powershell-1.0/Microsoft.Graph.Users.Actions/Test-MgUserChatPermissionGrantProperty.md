---
external help file: Microsoft.Graph.Users.Actions-help.xml
Module Name: Microsoft.Graph.Users.Actions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.users.actions/test-mguserchatpermissiongrantproperty
schema: 2.0.0
---

# Test-MgUserChatPermissionGrantProperty

## SYNOPSIS
Validate that a Microsoft 365 group's display name or mail nickname complies with naming policies.
Clients can use this API to determine whether a display name or mail nickname is valid before trying to create a Microsoft 365 group.
To validate the properties of an existing group, use the group: validateProperties function.
The following policy validations are performed for the display name and mail nickname properties:1.
Validate the prefix and suffix naming policy2.
Validate the custom banned words policy3.
Validate that the mail nickname is unique This API only returns the first validation failure that is encountered.
If the properties fail multiple validations, only the first validation failure is returned.
However, you can validate both the mail nickname and the display name and receive a collection of validation errors if you are only validating the prefix and suffix naming policy.
To learn more about configuring naming policies, see Configure naming policy.

> [!NOTE]
> To view the beta release of this cmdlet, view [Test-MgBetaUserChatPermissionGrantProperty](/powershell/module/Microsoft.Graph.Beta.Users.Actions/Test-MgBetaUserChatPermissionGrantProperty?view=graph-powershell-beta)

## SYNTAX

### ValidateExpanded (Default)
```
Test-MgUserChatPermissionGrantProperty -ChatId <String> -UserId <String> [-AdditionalProperties <Hashtable>]
 [-DisplayName <String>] [-EntityType <String>] [-MailNickname <String>] [-OnBehalfOfUserId <String>]
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Validate
```
Test-MgUserChatPermissionGrantProperty -ChatId <String> -UserId <String>
 -BodyParameter <IPaths1AicnihUsersUserIdChatsChatIdPermissiongrantsMicrosoftGraphValidatepropertiesPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ValidateViaIdentityExpanded
```
Test-MgUserChatPermissionGrantProperty -InputObject <IUsersActionsIdentity> [-AdditionalProperties <Hashtable>]
 [-DisplayName <String>] [-EntityType <String>] [-MailNickname <String>] [-OnBehalfOfUserId <String>]
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ValidateViaIdentity
```
Test-MgUserChatPermissionGrantProperty -InputObject <IUsersActionsIdentity>
 -BodyParameter <IPaths1AicnihUsersUserIdChatsChatIdPermissiongrantsMicrosoftGraphValidatepropertiesPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Validate that a Microsoft 365 group's display name or mail nickname complies with naming policies.
Clients can use this API to determine whether a display name or mail nickname is valid before trying to create a Microsoft 365 group.
To validate the properties of an existing group, use the group: validateProperties function.
The following policy validations are performed for the display name and mail nickname properties:1.
Validate the prefix and suffix naming policy2.
Validate the custom banned words policy3.
Validate that the mail nickname is unique This API only returns the first validation failure that is encountered.
If the properties fail multiple validations, only the first validation failure is returned.
However, you can validate both the mail nickname and the display name and receive a collection of validation errors if you are only validating the prefix and suffix naming policy.
To learn more about configuring naming policies, see Configure naming policy.

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: ValidateExpanded, ValidateViaIdentityExpanded
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
Type: IPaths1AicnihUsersUserIdChatsChatIdPermissiongrantsMicrosoftGraphValidatepropertiesPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Validate, ValidateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ChatId
The unique identifier of chat

```yaml
Type: String
Parameter Sets: ValidateExpanded, Validate
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
.

```yaml
Type: String
Parameter Sets: ValidateExpanded, ValidateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EntityType
.

```yaml
Type: String
Parameter Sets: ValidateExpanded, ValidateViaIdentityExpanded
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
Type: IUsersActionsIdentity
Parameter Sets: ValidateViaIdentityExpanded, ValidateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -MailNickname
.

```yaml
Type: String
Parameter Sets: ValidateExpanded, ValidateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnBehalfOfUserId
.

```yaml
Type: String
Parameter Sets: ValidateExpanded, ValidateViaIdentityExpanded
Aliases:

Required: False
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
Parameter Sets: ValidateExpanded, Validate
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

### Microsoft.Graph.PowerShell.Models.IPaths1AicnihUsersUserIdChatsChatIdPermissiongrantsMicrosoftGraphValidatepropertiesPostRequestbodyContentApplicationJsonSchema
### Microsoft.Graph.PowerShell.Models.IUsersActionsIdentity
## OUTPUTS

### System.Boolean
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IPaths1AicnihUsersUserIdChatsChatIdPermissiongrantsMicrosoftGraphValidatepropertiesPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: 
  - `[EntityType <String>]`: 
  - `[MailNickname <String>]`: 
  - `[OnBehalfOfUserId <String>]`: 

`INPUTOBJECT <IUsersActionsIdentity>`: Identity Parameter
  - `[AuthenticationMethodId <String>]`: The unique identifier of authenticationMethod
  - `[CalendarId <String>]`: The unique identifier of calendar
  - `[ChatId <String>]`: The unique identifier of chat
  - `[ChatMessageId <String>]`: The unique identifier of chatMessage
  - `[ChatMessageId1 <String>]`: The unique identifier of chatMessage
  - `[ContentTypeId <String>]`: The unique identifier of contentType
  - `[DeviceLogCollectionResponseId <String>]`: The unique identifier of deviceLogCollectionResponse
  - `[DocumentSetVersionId <String>]`: The unique identifier of documentSetVersion
  - `[DriveId <String>]`: The unique identifier of drive
  - `[DriveItemId <String>]`: The unique identifier of driveItem
  - `[DriveItemVersionId <String>]`: The unique identifier of driveItemVersion
  - `[EventId <String>]`: The unique identifier of event
  - `[EventId1 <String>]`: The unique identifier of event
  - `[ListItemId <String>]`: The unique identifier of listItem
  - `[ListItemVersionId <String>]`: The unique identifier of listItemVersion
  - `[MailFolderId <String>]`: The unique identifier of mailFolder
  - `[MailFolderId1 <String>]`: The unique identifier of mailFolder
  - `[ManagedDeviceId <String>]`: The unique identifier of managedDevice
  - `[MessageId <String>]`: The unique identifier of message
  - `[NotebookId <String>]`: The unique identifier of notebook
  - `[OnenotePageId <String>]`: The unique identifier of onenotePage
  - `[OnenoteSectionId <String>]`: The unique identifier of onenoteSection
  - `[PermissionId <String>]`: The unique identifier of permission
  - `[PhoneAuthenticationMethodId <String>]`: The unique identifier of phoneAuthenticationMethod
  - `[ResourceSpecificPermissionGrantId <String>]`: The unique identifier of resourceSpecificPermissionGrant
  - `[SubscriptionId <String>]`: The unique identifier of subscription
  - `[TeamsAppInstallationId <String>]`: The unique identifier of teamsAppInstallation
  - `[TodoTaskId <String>]`: The unique identifier of todoTask
  - `[TodoTaskListId <String>]`: The unique identifier of todoTaskList
  - `[UserId <String>]`: The unique identifier of user

## RELATED LINKS
[Test-MgBetaUserChatPermissionGrantProperty](/powershell/module/Microsoft.Graph.Beta.Users.Actions/Test-MgBetaUserChatPermissionGrantProperty?view=graph-powershell-beta)

