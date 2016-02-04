# Array.collect<'T,'U> Function (F#)

For each element of the array, applies the given function. Concatenates all the results and return the combined array.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD



```


// Signature:
Array.collect : ('T -> 'U []) -> 'T [] -> 'U []

// Usage:
Array.collect mapping array


```



#### CAPS_PARAMETERS_MD
*mapping*
Type: **'T -&gt; 'U**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The function to create sub-arrays from the input array elements.


*array*
Type: **'T**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The input array.



**The concatenation of the subarrays.****The following code demonstrates the use of Array.collect to concatenate subarrays that are generated from each array element.**


```



printfn "%A" (Array.collect (fun elem -> [| 0 .. elem |]) [| 1; 5; 10|])


```



**[|0; 1; 0; 1; 2; 3; 4; 5; 0; 1; 2; 3; 4; 5; 6; 7; 8; 9; 10|]**
## CAPS_REMARKS_MD
This function is named **Collect** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+%28F%23%29.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+%28F%23%29.md)
