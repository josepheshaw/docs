# GETCWD

<PageHeader />  

**Tags:**
<badge text='directories' vertical='middle' />

## Description

This function returns the current working directory of the program, which is normally the directory in which execution of the program occurred but possibly changed using the [CHDIR](./../chdir) function. It takes the general form:

```
 GETCWD(Var)
```

Where **Var** will be set to the name of the current working directory at execution.

The function itself returns a boolean **TRUE** or **FALSE** value to indicate whether the command was successful or not.

## Note

> Refer to underlying operating system documentation for more information on the concept of the current working directory.

An example of use is as follows:

```
IF GETCWD(work_Dir) THEN
    CRT "Current Working Directory = " : work_Dir
END ELSE
    CRT "Could not determine CWD!"
END
```

Go back to [jBASE BASIC](./../README.md)

Go back to [Programmers' Reference Guide](./../../reference-guides/jbc/README.md)

<PageFooter />
