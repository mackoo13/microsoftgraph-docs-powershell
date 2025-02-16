---
external help file: Microsoft.Graph.Beta.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Beta.Identity.SignIns
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.identity.signins/get-mgbetatrustframeworkpolicycount
schema: 2.0.0
ms.prod: identity-and-sign-in
ms.prod: identity-and-sign-in
---

# Get-MgBetaTrustFrameworkPolicyCount

## SYNOPSIS
Get the number of the resource

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [Get-MgUserAuthenticationEmailMethod](/powershell/module/Microsoft.Graph.Identity.SignIns/Get-MgUserAuthenticationEmailMethod?view=graph-powershell-1.0)

## SYNTAX

```
Get-MgBetaTrustFrameworkPolicyCount [-Filter <String>] [-Search <String>] [<CommonParameters>]
```

## DESCRIPTION
Get the number of the resource

## EXAMPLES
### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Beta.Identity.SignIns

# A UPN can also be used as -UserId.
Get-MgBetaUserAuthenticationEmailMethod -UserId $userId

```
This example shows how to use the Get-MgBetaUserAuthenticationEmailMethod Cmdlet.


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
[Get-MgUserAuthenticationEmailMethod](/powershell/module/Microsoft.Graph.Identity.SignIns/Get-MgUserAuthenticationEmailMethod?view=graph-powershell-1.0)
