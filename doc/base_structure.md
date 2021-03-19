# Information

PORI is linear traditional programming language. This means it is executed from top to the bottom. It's structure is similar to more famous programming languages, such as basic and php, but due it's novelty, it lacks of the more detailed and advanced operators.

Most important, PORI aims not be well-structure, modern nor efficient. It was created for the fun of it so it you grow grey hairs because of it, you need restructure your thinking. IF author is asked, it's has still better syntax than python /s.

# Code structure

# File format

File format support both UNIX and WINDOWS linefeeds. UTF-8 is needed due code format containing scandinavic special characters characteristic to a Finnish language and usage in the code. Code is incase sensitive.

# Basic structure

PORI is compiled/executed between open-tag **eläks_viel** and closing-tag **koit_pärjäil**. All lines must end with a **period** (.). I could have used semi-colon like most of the programming languages, but due the fact people of Pori are blunt, period felt being more proper.

### Example: Basic program with start and end

    eläks_viel.
    
    koit_pärjäil.
    
# Basic output functions

## Sössötä *"text" or variable*

Prints directly out text to console (stdout) surrounded by double-quotes (") or if no double-quotes defined, assumes variable is being used. If you want to declare variable inside the double-quotes, you can add *%variable%* into the text.

## Mäikätä *"text" or variable*

Otherwise similar operation to **sössötä** but outputs text as all-caps.

### Example: Basic program with output

    eläks_viel.
    sössötä "tuu porriin pistetään sut pärekorriin".
    koit_pärjäil.

This program should output should be following:

    tuu porriin pistetään sut pärekorriin
    ässät

# Variable decleration

## tos_o *variable_name*
    
Defines *variable_name* named variable. Can be used both as a numeral and string variables.

# Basic input functions

## Kuulustel *variablename*
*alias: kuulostel*

Provides stdin (console) and stores in into variable **variablename** which can be used later. If variable is not defined earlier, will give error **pölvästi**

### Example: Basic program with variable decleration, input readout and its output

    eläks_viel.
    tos_o user_input.
    sössötä "Who are you".
    kuulustel user_input.
    sössötä "You are %user_input%".
    koit_pärjäil.    

#  Math functions

## Nulju *numbervariable* *amount*
*alias: pihi*
 
Decreases value of the numeral variable *numbervariable* by *amount*. If provided variable is not a numeral, will give error **pölvästi**

### Example: Basic program removes value

   eläks_viel.
   tos_o user_input.
   sössötä "Enter number".
   kuulustel user_input.
   Nulju user_input 10
   sössötä "Here is that number with ten less: %user_input%".
   koit_pärjäil.

# File functions

## Kampraati *filename*
*alias: kamraari*
    
Sideloads other PORI-based code script and runs it. Fails in code error and stops all execution.

# Execution commands

## Ei mittää

Safely terminates code execution. Automatically run after end of the code.

## Funderaat *seconds*
*alias: funteerat*
    
Pauses code execution for *seconds*

## Rauma

Terminates code execution with error. Using this command is a bad practice.

# Execution outputs

## Pölvästi *linenumber*
    
There was a error in the code on line *linenumber* which has stopped the execution. Program cannot continue.

## Ässät

Program/code was executed succusfully. Always displayed after succesful execution.
