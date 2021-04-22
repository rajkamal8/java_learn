# some acronyms

jre  : java runtime environment
it enables java code execution

jdk : java development kit
it provide tools required to create java apps

ide : integrated development environment
it helps to edit run and debug our programs

## type of comments

> single line comment : //  ignores the content after
> block line comment : /* */  it an cover up multiline comments

javadoc comment :   /** */  it also work similar to block line comment .
it can be used to generate documentation with help of an ide.

## JAVA PACKAGES

java packages are created with domain names to ensure uniqueness .
example: com.google.help .
> it stores java files in folder created named <package> inside src folder .

## how to initaize an array in java

float[] values = new float[3];

## for-each loop

executes statement once for each array member
handles getting collection length
handles accessing each values

syntax:
for(float index_variable : array_variable)
{
    // index_variable is equal to array_variable[0]
}

## command line arguments

how to give a parameter to command line arguments like { public static void main (String[] args)}

using command line type
java <package_name if any >.<java file name> and the pass parameter with space between them.
to access these values use array indexing method args[0],args[1],args[2] ., etc .
these values that are accepted are in string format convert to the desired type before using .

syntax :
C://java_program/calengine/out/production/calcengine java com.pluralsight.calcengine hello "mary jane" ......