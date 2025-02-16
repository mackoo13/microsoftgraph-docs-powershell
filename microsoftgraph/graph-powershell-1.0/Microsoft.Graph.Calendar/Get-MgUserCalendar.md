---
external help file: Microsoft.Graph.Calendar-help.xml
Module Name: Microsoft.Graph.Calendar
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.calendar/get-mgplacecountasroomlist
schema: 2.0.0
---

# Get-MgPlaceCountAsRoomList

## SYNOPSIS
Get the number of the resource

> [!NOTE]
> To view the beta release of this cmdlet, view [Get-MgBetaUserCalendar](/powershell/module/Microsoft.Graph.Beta.Calendar/Get-MgBetaUserCalendar?view=graph-powershell-beta)

## SYNTAX

```
Get-MgPlaceCountAsRoomList [-Filter <String>] [-Search <String>] [<CommonParameters>]
```

## DESCRIPTION
Get the number of the resource

## EXAMPLES
### Example 1: Code snippet

```powershell
Import-Module Microsoft.Graph.Calendar

# A UPN can also be used as -UserId.
Get-MgUserCalendar -UserId $userId
```
This example shows how to use the Get-MgUserCalendar Cmdlet.

To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).


## PARAMETERS

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

### -Search
Search items by search phrases

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Int32
## NOTES

ALIASES

## RELATED LINKS
[Get-MgBetaUserCalendar](/powershell/module/Microsoft.Graph.Beta.Calendar/Get-MgBetaUserCalendar?view=graph-powershell-beta)
