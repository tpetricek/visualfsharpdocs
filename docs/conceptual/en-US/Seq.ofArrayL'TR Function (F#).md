# Seq.ofArray<'T> Function (F#)

Views the given array as a sequence.

**Namespace/Module Path**: Microsoft.FSharp.Collections.Seq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD



```


// Signature:
Seq.ofArray : 'T array -> seq<'T>

// Usage:
Seq.ofArray source


```



#### CAPS_PARAMETERS_MD
*source*
Type: **'T array**


The input array.



**exceptions tag is not supported!!!!**
**The result sequence.**
## CAPS_REMARKS_MD
This function is named **OfArray** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code shows how to use Seq.ofArray.**


```



    let seq1 = Array.init 10 (fun index -> index.ToString()) 
               |> Seq.ofArray


```



**F# Interactive Output**
**val seq1 : seq&lt;string&gt;**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Seq Module &#40;F&#35;&#41;](Collections.Seq+Module+%28F%23%29.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+%28F%23%29.md)
