Text File Contents Transpose
============================

Text File Contents Transpose is a simple application that is able to take either a single or multi-line text file and transpose its contents. So a multi-line file will be forced into a single line file, using the specified delimiter character to separate the entries while a single line file will be split into multiple lines, using the specified delimiter character to split the line on.

For example (using ';;'):
   aa
   bb
becomes
   aa;;bb (and vice versa)

Usage: executable [affected filename] [input type] [delimiter] [error level]
  where:
   - [affected filename]: the text file to be parsed
   - [input type]: (single, multiple) the input file's current layout
   - [delimiter]: string used to either concat or split lines on
   - [error level]: the level of error reporting (full, minimal, none)

Created by Craig Lotter, December 2005

*********************************

Project Details:

Coded in Visual Basic .NET using Visual Studio .NET 2003
Implements concepts such as string manipulation and file handling.
Level of Complexity: simple
