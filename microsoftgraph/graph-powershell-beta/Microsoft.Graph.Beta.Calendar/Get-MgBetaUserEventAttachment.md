---
external help file: Microsoft.Graph.Beta.Calendar-help.xml
Module Name: Microsoft.Graph.Beta.Calendar
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.calendar/get-mgbetauserdefaultcalendarevent
schema: 2.0.0
ms.prod: outlook
ms.prod: outlook
---

# Get-MgBetaUserDefaultCalendarEvent

## SYNOPSIS
Retrieve a list of events in a calendar.
The calendar can be one for a user, or the default calendar of a Microsoft 365 group.
The list of events contains single instance meetings and series masters.
To get expanded event instances, you can get the calendar view, orget the instances of an event.

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [Get-MgUserEventAttachment](/powershell/module/Microsoft.Graph.Calendar/Get-MgUserEventAttachment?view=graph-powershell-1.0)

## SYNTAX

```
Get-MgBetaUserDefaultCalendarEvent -UserId <String> [-ExpandProperty <String[]>] [-Filter <String>]
 [-Property <String[]>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-PageSize <Int32>] [-All]
 [-CountVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
Retrieve a list of events in a calendar.
The calendar can be one for a user, or the default calendar of a Microsoft 365 group.
The list of events contains single instance meetings and series masters.
To get expanded event instances, you can get the calendar view, orget the instances of an event.

## EXAMPLES
### Example 1: Code snippet

```powershell
Import-Module Microsoft.Graph.Beta.Calendar

# A UPN can also be used as -UserId.
Remove-MgBetaUserEventAttachment -UserId $userId -EventId $eventId -AttachmentId $attachmentId
```
This example shows how to use the Get-MgBetaBetaUserEventAttachment Cmdlet.

To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).


## PARAMETERS

### -All
List all pages.

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

### -CountVariable
Specifies a count of the total number of items in a collection.
By default, this variable will be set in the global scope.

```yaml
Type: String
Parameter Sets: (All)
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
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PageSize
Sets the page size of results.

```yaml
Type: Int32
Parameter Sets: (All)
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

### -Sort
Order items by property values

```yaml
Type: String[]
Parameter Sets: (All)
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
Parameter Sets: (All)
Aliases: Limit

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
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Skip
Skip the first n items

```yaml
Type: Int32
Parameter Sets: (All)
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

## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphEvent
## NOTES

ALIASES

## RELATED LINKS
[Get-MgUserEventAttachment](/powershell/module/Microsoft.Graph.Calendar/Get-MgUserEventAttachment?view=graph-powershell-1.0)
