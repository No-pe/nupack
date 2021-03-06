# NuPack
Visual Studio extension to build NuGet package

# Visual Studio Gallery
[Download]https://visualstudiogallery.msdn.microsoft.com/d9a0cb72-99f5-4186-9149-0a9b8ab82356

# Update Log
V1.4.4 11/10/2016
* Fix a bug when sync version to other .nuspec file in the solution.

V1.4.3 11/8/2016
* Fix a bug of assembly info modification.

V1.4.2 10/27/2016
* Dependency merge bug fix.

V1.4.1 10/20/2016
* TFS check out bug fix(some .dll missed).

V1.4 8/4/2016
+ Sync version to .nuspec file in solution projects which depend on it when a package's version has changed.
* .nuspec merge bug fix when dependencies in multiple groups 
* Encode whitespaces in XML

V1.3.2 7/26/2016
+ Add feature which supports to remember NuGet API key.

V1.3.1 7/20/2016
* Fix a bug of merge dependency in separated groups. 

V1.3 6/23/2016
+ Add VB project support.

V1.2 6/4/2016
* Improve deploy wizard.
* Merge dependencies from packages.config automatically where .nuspec file created.

V1.1.1 5/24/2016
+ Merge dependencies from packages.config into .nuspec automatically.
* Improve replacement pattern for assemblyinfo.cs under multi language charset.

V1.1 5/17/2016
+ Add nuspec dependency management.
+ Add NuGet.exe path and output directory settings.
+ Display NuGet command output message in Output Pane in VS.
* Adjust context menu positions.
* Some nuspec bug fixed.
* Some assemblyinfo.cs replacement bug fixed.

V1.0 3/13/2016
+ Initial version with basic features.