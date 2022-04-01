# Variables-and-Comparison-Operators-Tasks

# Ejercicio 1. Assign a variable with each datatypes covered in the previous workshop
```
$BoolanVar = $True
$StringVar = "This is a string"
$IntVar = 42
```

# Ejercicio 2. List all variables currently loaded in to memory.
```
PS C:\Users\Fran\Documents\Ejercicio3SI> Get-Variable

Name                           Value
----                           -----
$                              42
?                              True
^                              $IntVar
args                           {}
BoolanVar                      True
ConfirmPreference              High
ConsoleFileName
DebugPreference                SilentlyContinue
Error                          {}
ErrorActionPreference          Continue
ErrorView                      NormalView
ExecutionContext               System.Management.Automation.EngineIntrinsics
false                          False
FormatEnumerationLimit         4
HOME                           C:\Users\Fran
Host                           System.Management.Automation.Internal.Host.InternalHost
InformationPreference          SilentlyContinue
input                          System.Collections.ArrayList+ArrayListEnumeratorSimple
IntVar                         42
MaximumAliasCount              4096
MaximumDriveCount              4096
MaximumErrorCount              256
MaximumFunctionCount           4096
MaximumHistoryCount            4096
MaximumVariableCount           4096
MyInvocation                   System.Management.Automation.InvocationInfo
NestedPromptLevel              0
null
OutputEncoding                 System.Text.ASCIIEncoding
PID                            4940
PROFILE                        C:\Users\Fran\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1
ProgressPreference             Continue
PSBoundParameters              {}
PSCommandPath
PSCulture                      es-ES
PSDefaultParameterValues       {}
PSEdition                      Desktop
PSEmailServer
PSHOME                         C:\Windows\System32\WindowsPowerShell\v1.0
PSScriptRoot
PSSessionApplicationName       wsman
PSSessionConfigurationName     http://schemas.microsoft.com/powershell/Microsoft.PowerShell
PSSessionOption                System.Management.Automation.Remoting.PSSessionOption
PSUICulture                    es-ES
PSVersionTable                 {PSVersion, PSEdition, PSCompatibleVersions, BuildVersion...}
PWD                            C:\Users\Fran\Documents\Ejercicio3SI
ShellId                        Microsoft.PowerShell
StackTrace
StringVar                      This is a string
true                           True
VerbosePreference              SilentlyContinue
WarningPreference              Continue
WhatIfPreference               False
```

# Ejercicio 3. Multiple two Int variables together
```
PS C:\Users\Fran\Documents\Ejercicio3SI> $IntVar1 = 4
PS C:\Users\Fran\Documents\Ejercicio3SI> $IntVar2 = 10
PS C:\Users\Fran\Documents\Ejercicio3SI> $IntVar1 * $IntVar2
40
```
# Ejercicio 4. First declare two Int variables. Then divided the first variable by the second and assign the result to a variable named $VariableResult
```
PS C:\Users\Fran\Documents\Ejercicio3SI> $VariableResult = $IntVar1 / $IntVar2
PS C:\Users\Fran\Documents\Ejercicio3SI> $VariableResult
0,4
```

# Ejercicio 5. Typecast a Variable as a “String” and assign it a value of 5
```
[String]$TypecastVar = 5
```
