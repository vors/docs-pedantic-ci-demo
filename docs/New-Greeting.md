---
external help file: Greet-help.xml
Module Name: Greet
online version:
schema: 2.0.0
---

# New-Greeting

## SYNOPSIS
Greet people

## SYNTAX

```
New-Greeting [-Name] <String> [<CommonParameters>]
```

## DESCRIPTION
Greet people with Hello

## EXAMPLES

### Example 1
```powershell
PS C:\> 'a'..'z' | New-Greeting
```

```
Hello a
Hello b
Hello c
Hello d
Hello e
Hello f
Hello g
Hello h
Hello i
Hello j
Hello k
Hello l
Hello m
Hello n
Hello o
Hello p
Hello q
Hello r
Hello s
Hello t
Hello u
Hello v
Hello w
Hello x
Hello y
Hello z
```

Greet personz 'a'-'z' and pass the value from the pipeline

## PARAMETERS

### -Name
Name of the person to greet

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS
