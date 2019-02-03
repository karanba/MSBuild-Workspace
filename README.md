# MSBUILD



## Introduction & Basics

MSBuilds is a;

* A software building tool,

* Needed to know as a dot.net developer.

* It gets benefit to know MSBUild. 

* An interpreted programming language expressed as in XML

MSBuild XML file interpreted by MSBuild.exe

* If dot.net framework installed you have MSBuild.exe

* Can be invoked by command line and also with Visual Studio (F5, CTRL + F5), and also inside TFS 

* MSBuid capabilities can be extend beside building and executing related tasks.

* Can be used as a general purpose automation tool.


### Hello World! :earth_africa:

Root element for an msbuild file must be *Project* and xml namesspace is *http://schemas.microsoft.com/developer/msbuild/2003*   

```xml
<?xml version="1.0" encoding="utf-8"?>
<Project xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
    <Target name="hello-world">
        <Message text="Hello, World!" />>
    </Target>
</Project>
```

:runner: _to run this file_; 

```powershell
msbuild .\src\hello-world.msbuild
```
:scroll: _output:_

```powershell

Project "C:\repo\GitHub\MSBuild-Workspace\src\hello-world.msbuild" on node 1 (default targets).
HelloWorld:
  Hello, World!
Done Building Project "C:\repo\GitHub\MSBuild-Workspace\src\hello-world.msbuild" (default targets).


Build succeeded.
    0 Warning(s)
    0 Error(s)
```

### Where is MSBuild.exe :mag: 

Inside .net framework folder;
```powershell
C:\Windows\Microsoft.NET\Framework\v4.0.30319\MSBuild.exe
```
Also _msbuild.exe.config_,  _MSBuild.rsp_ file and _MSBuild_ folder is there which holds _xsd_ files that define the structure inside msbuild xml file.

``` bash
 MSBUild /
 ---- Microsoft.Build.Commontypes.xsd
 ---- Microsoft.Build.Core.xsd
```

Inside Visual Studio Installation folder;
```powershell
TODO: Add Path
```

### Targets




### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
