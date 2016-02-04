# Array.empty<'T> Type Function (F#)

Returns an empty array of the given type.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD



```


// Signature:
Array.empty<'T> :  'T []

// Usage:
Array.empty


```


**An empty array.**
## CAPS_REMARKS_MD
This function is named **Empty** in compiled assemblies. If you are accessing the function from a .NET language other than F#, or through reflection, use this name.

**The following code shows how to use Array.empty.**


```



    // Specify the type by using a type argument.
    let array1 = Array.empty<int>
    // Specify the type by using a type annotation.
    let array2 : int array = Array.empty

    // Even though array3 has a generic type,
    // you can still use methods such as Length on it.
    let array3 = Array.empty
    printfn "Length of empty array: %d" array3.Length


```



**Output**
**Length of empty array: 0**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+%28F%23%29.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+%28F%23%29.md)
