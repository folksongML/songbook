# Folksong Markup Language

Aim: create a tool to convert a very simple markup language into a songbook.

## Specification
### SP1
The nature of each line to be defined by the first two letters from each line followed by a space:
* v1 verse 1
* c1 chorus 1
* r1 response 1

### SP2
The ability to specify where each text block will be displayed as a input string with the same syntax as those described above.

### SP3
The ability to parse very simple songs without the above syntax giving a user command.
e.g. script.py "v1 c1 v2 v3 v4"
will look for five blocks text and identify each as first one chorus 1 verse 2 3 and 4 respectively.

## Work in progress:
1. Create acceptance test files
2. Create the software described in SP3
