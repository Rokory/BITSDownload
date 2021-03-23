# BITSDownload

## Getting started

It is recommended to copy the folder BITSDownload to one of the folders indicated by the $env:PSModulePath variable (e. g. %userprofile%\Documents\WindowsPowerShell\Modules).

First, import the module.

````powershell
Import-Module <String>
````

You can either use the module name or the full path, if you did not copy the module to one of the paths in $env:PSModulePath.

To find information about useage, use ```Get-Help``` followed by the cmdlet in the module

## Invoke-BitsTransfer

Simple cmdlet to start a synchronous download of a file using BITS. Demonstrates handling of multiple pipeline values and the usage of a progress bar.