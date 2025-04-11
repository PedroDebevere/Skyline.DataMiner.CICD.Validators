﻿---  
uid: Validator_3_38_2  
---

# CheckAssemblies

## UnconsolidatedPackageReference\_Sub

### Details

When multiple QActions are using different versions of a NuGet package, it can lead to runtime exceptions such as MissingMethodException or InvalidCastException.  
To fix these issues, it is important to use the same version of a NuGet package across the entire solution.  
'Skyline.DataMiner.Dev.\*' (aka DevPacks) or 'Skyline.DataMiner.Files.\*' NuGet packages should also be aligned across all projects of the solution as these packages represent the DataMiner version that is being developed against.
