# JetBrains ReSharper Annotations - C# Internal Implementation

ReSharper Annotations help reduce false positive warnings, explicitly declare purity and nullability in your code, deal with implicit usages of members, support special semantics of APIs in ASP.NET and XAML frameworks and otherwise increase accuracy of ReSharper code inspections.

This package is a clone of the JetBrains.Annotations project by JetBrains, but not resulting in a public .dll that could prove to collide with other implementations, but resulting in an internal code contribution that will not collide externally.

> For some reason the Nuget team decided that the content files feature is [not (yet) available for .net Core projects](http://blog.nuget.org/20160126/nuget-contentFiles-demystified.html). In this situation you might want to consider downloading [the actual file](https://raw.githubusercontent.com/bepost/jetbrains-annotations-internal/master/src/JetBrains.Annotations/JetBrains.Annotations.cs) and using this in your code. The file has all the required annotations and pragma's to make sure you won't get warnings about file locations and inconsistent naming.

		
All credits for the actual functionality goes to the JetBrains team.