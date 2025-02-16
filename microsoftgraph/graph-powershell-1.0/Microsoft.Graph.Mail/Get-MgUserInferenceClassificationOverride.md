---
external help file: Microsoft.Graph.Mail-help.xml
Module Name: Microsoft.Graph.Mail
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.mail/get-mguserinferenceclassification
schema: 2.0.0
ms.prod: mail
---

# Get-MgUserInferenceClassification

## SYNOPSIS
Relevance classification of the user's messages based on explicit designations which override inferred relevance or importance.

> [!NOTE]
> To view the beta release of this cmdlet, view [Get-MgBetaUserInferenceClassificationOverride](/powershell/module/Microsoft.Graph.Beta.Mail/Get-MgBetaUserInferenceClassificationOverride?view=graph-powershell-beta)

## SYNTAX

### Get (Default)
```
Get-MgUserInferenceClassification -UserId <String> [-Property <String[]>] [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgUserInferenceClassification -InputObject <IMailIdentity> [-Property <String[]>] [<CommonParameters>]
```

## DESCRIPTION
Relevance classification of the user's messages based on explicit designations which override inferred relevance or importance.

## EXAMPLES
### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Mail

# A UPN can also be used as -UserId.
Get-MgUserInferenceClassificationOverride -UserId $userId

```
This example shows how to use the Get-MgUserInferenceClassificationOverride Cmdlet.


## PARAMETERS

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IMailIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### -UserId
The unique identifier of user

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IMailIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphInferenceClassification
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`INPUTOBJECT <IMailIdentity>`: Identity Parameter
  - `[AttachmentId <String>]`: The unique identifier of attachment
  - `[ExtensionId <String>]`: The unique identifier of extension
  - `[InferenceClassificationOverrideId <String>]`: The unique identifier of inferenceClassificationOverride
  - `[MailFolderId <String>]`: The unique identifier of mailFolder
  - `[MailFolderId1 <String>]`: The unique identifier of mailFolder
  - `[MessageId <String>]`: The unique identifier of message
  - `[MessageRuleId <String>]`: The unique identifier of messageRule
  - `[UserId <String>]`: The unique identifier of user

## RELATED LINKS
[Get-MgBetaUserInferenceClassificationOverride](/powershell/module/Microsoft.Graph.Beta.Mail/Get-MgBetaUserInferenceClassificationOverride?view=graph-powershell-beta)
