# @unassigned

<PageHeader />

## Description

Unassigns a variable.

## Examples

```
x = 1
CRT x
x = @unassigned
CRT x   ;* The debugger is entered at this point
```

```
OPEN "MD" TO md ELSE STOP 201, "MD"
md = @unassigned
READ rec FROM md, 'LIST'  ;* The debugger is entered at this point as md is no longer a valid file descriptor
CRT rec<1>
```

Go back to [jBASE BASIC](./../README.md)

Go back to [Programmers' Reference Guide](./../../reference-guides/jbc/README.md)

<PageFooter />
