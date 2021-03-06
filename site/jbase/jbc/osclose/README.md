# OSCLOSE

<PageHeader />  

**Tags:**
<badge text='file handling' vertical='middle' />

## Description

The **OSCLOSE** command closes a sequential file that was previously opened with the [OSOPEN](./../osopen) or [OPENSEQ](./../openseq) command. the command takes the general form:

```
OSCLOSE file.var [ON ERROR statements]
```

Where:

- **file.var** Specifies the file to close.
- ON ERROR **statements** Specifies statements to execute if the **OSCLOSE** statement fails with a fatal error because the file is not open, an I/O error occurs, or jBASE cannot find the file.

If the **ON ERROR** clause is not specified,  and a fatal error occurs, the program will enter the debugger. After execution of **OSCLOSE**, the [STATUS](./../status-function) function returns either 0 or a failure code.

| Code | Description |
| --- | --- |
| 0 | The file was closed successfully. |
| 1 | Close failed. |

An example of use is as:

```
OSCLOSE MYFILE_VARIABLE
```

Go back to [jBASE BASC](./../jbase-basic-programmers-reference-guide).

Go back to [Programmers' Reference Guide](./../../reference-guides/jbc/README.md)

<PageFooter />
