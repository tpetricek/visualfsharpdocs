# OperatorIntrinsics.RangeStepGeneric<'Step,'T> Function (F#)

Generates a range of values using the given zero, add, start, step and stop values.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators.OperatorIntrinsics

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD



```


// Signature:
RangeStepGeneric : 'Step -> ('T -> 'Step -> 'T) -> 'T -> 'Step -> 'T -> seq<'T>

// Usage:
RangeStepGeneric zero add start step stop


```



#### CAPS_PARAMETERS_MD
*zero*
Type: **'Step**


The zero value for the step type.


*add*
Type: **'T -&gt; 'Step -&gt; 'T**


An addition function that adds a value and the step to produce another value.


*start*
Type: **'T**


The starting value.


*step*
Type: **'Step**


The increment to the value on each iteration.


*stop*
Type: **'T**


The final value.



**An enumerable sequence of values starting with start, incrementing by step, and ending with stop.**
## CAPS_REMARKS_MD
This function is for use by compiled F# code and should not be used directly.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable, Portable




## See Also
[Operators.OperatorIntrinsics Module &#40;F&#35;&#41;](Operators.OperatorIntrinsics+Module+%28F%23%29.md)

[Core.Operators Module &#40;F&#35;&#41;](Core.Operators+Module+%28F%23%29.md)
