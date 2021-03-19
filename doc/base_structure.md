# Information

PORI is linear traditional programming language. This means it is executed from top to the bottom. It's structure is similar to more famous programming languages, such as basic and php, but due it's novelty, it lacks of the more detailed and advanced operators.

Most important, PORI aims not be well-structure, modern nor efficient. It was created for the fun of it so it you grow grey hairs because of it, you need restructure your thinking.

# Code structure

# File format

File format support both UNIX and WINDOWS linefeeds. UTF-8 is needed due code format containing scandinavic special characters characteristic to a Finnish language and usage in the code. Code is incase sensitive.

# Basic structure

PORI is compiled/executed between open-tag **eläks_viel** and closing-tag **koit_pärjäil**. All lines must end with a **period** (.). I could have used semi-colon like most of the programming languages, but due the fact people of Pori are blunt, period felt being more proper.

## Very simple executing and terminating code example without content

    eläks_viel.
    
    koit_pärjäil.
    
# Basic output functions

## Sössötä

Prints directly out text to console (stdout) surrounded by double-quotes (") or if no double-quotes defined, assumes variable is being used. These cannot be combined.

## Mäikätä

Otherwise similar operation to **sössötä** but outputs text as all-caps.

# Basic input functions

## Kuulustel **variablename**
*alias: kuulostel*

Provides stdin (console) and stores in into variable **variablename** which can be used later. If variable is not defined earlier, will give error **pölvästi**

*** this will be updated later ***
