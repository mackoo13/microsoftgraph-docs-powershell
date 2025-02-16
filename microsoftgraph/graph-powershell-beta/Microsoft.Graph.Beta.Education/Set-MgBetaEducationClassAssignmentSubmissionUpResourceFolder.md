---
external help file: Microsoft.Graph.Beta.Education-help.xml
Module Name: Microsoft.Graph.Beta.Education
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.education/set-mgbetaeducationclassassignmentsubmissionupresourcefolder
schema: 2.0.0
---

# Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder

## SYNOPSIS
Trigger the creation of the SharePoint resource folder where all file-based resources (Word, Excel, and so on) should be uploaded for a given submission.
Only teachers and students can perform this operation.
Note that files must be located in this folder in order to be added as resources.
Only a student in the class can determine what files to upload in a given submission-level resource folder.

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [Set-MgEducationClassAssignmentSubmissionUpResourceFolder](/powershell/module/Microsoft.Graph.Education/Set-MgEducationClassAssignmentSubmissionUpResourceFolder?view=graph-powershell-1.0)

## SYNTAX

### Set (Default)
```
Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder -EducationAssignmentId <String>
 -EducationClassId <String> -EducationSubmissionId <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### SetViaIdentity
```
Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder -InputObject <IEducationIdentity> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Trigger the creation of the SharePoint resource folder where all file-based resources (Word, Excel, and so on) should be uploaded for a given submission.
Only teachers and students can perform this operation.
Note that files must be located in this folder in order to be added as resources.
Only a student in the class can determine what files to upload in a given submission-level resource folder.

## EXAMPLES
### Example 1: Using the Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder Cmdlet
```powershell
Import-Module Microsoft.Graph.Beta.Education
$params = @{
}
Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder -EducationClassId $educationClassId -EducationAssignmentId $educationAssignmentId -EducationSubmissionId $educationSubmissionId -BodyParameter $params
```
This example shows how to use the Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).
### Example 2: Using the Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder Cmdlet
```powershell
Import-Module Microsoft.Graph.Beta.Education
$params = @{
}
Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder -EducationClassId $educationClassId -EducationAssignmentId $educationAssignmentId -EducationSubmissionId $educationSubmissionId -BodyParameter $params
```
This example shows how to use the Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).
### Example 3: Using the Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder Cmdlet
```powershell
Import-Module Microsoft.Graph.Beta.Education
$params = @{
}
Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder -EducationClassId $educationClassId -EducationAssignmentId $educationAssignmentId -EducationSubmissionId $educationSubmissionId -BodyParameter $params
```
This example shows how to use the Set-MgBetaEducationClassAssignmentSubmissionUpResourceFolder Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

## PARAMETERS

### -EducationAssignmentId
The unique identifier of educationAssignment

```yaml
Type: String
Parameter Sets: Set
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EducationClassId
The unique identifier of educationClass

```yaml
Type: String
Parameter Sets: Set
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EducationSubmissionId
The unique identifier of educationSubmission

```yaml
Type: String
Parameter Sets: Set
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
Type: IEducationIdentity
Parameter Sets: SetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### Microsoft.Graph.Beta.PowerShell.Models.IEducationIdentity
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphEducationSubmission
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`INPUTOBJECT <IEducationIdentity>`: Identity Parameter
  - `[EducationAssignmentId <String>]`: The unique identifier of educationAssignment
  - `[EducationAssignmentResourceId <String>]`: The unique identifier of educationAssignmentResource
  - `[EducationCategoryId <String>]`: The unique identifier of educationCategory
  - `[EducationClassId <String>]`: The unique identifier of educationClass
  - `[EducationGradingCategoryId <String>]`: The unique identifier of educationGradingCategory
  - `[EducationModuleId <String>]`: The unique identifier of educationModule
  - `[EducationModuleResourceId <String>]`: The unique identifier of educationModuleResource
  - `[EducationOutcomeId <String>]`: The unique identifier of educationOutcome
  - `[EducationRubricId <String>]`: The unique identifier of educationRubric
  - `[EducationSchoolId <String>]`: The unique identifier of educationSchool
  - `[EducationSubmissionId <String>]`: The unique identifier of educationSubmission
  - `[EducationSubmissionResourceId <String>]`: The unique identifier of educationSubmissionResource
  - `[EducationSynchronizationErrorId <String>]`: The unique identifier of educationSynchronizationError
  - `[EducationSynchronizationProfileId <String>]`: The unique identifier of educationSynchronizationProfile
  - `[EducationUserId <String>]`: The unique identifier of educationUser

## RELATED LINKS
[Set-MgEducationClassAssignmentSubmissionUpResourceFolder](/powershell/module/Microsoft.Graph.Education/Set-MgEducationClassAssignmentSubmissionUpResourceFolder?view=graph-powershell-1.0)
