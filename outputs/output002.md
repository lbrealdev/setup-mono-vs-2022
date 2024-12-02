```
Build started at 15:22...
1>------ Build started: Project: ExampleDotNetLib.Tests, Configuration: Debug Any CPU ------
1>Build started 02/12/2024 15:22:16.
1>GenerateTargetFrameworkMonikerAttribute:
1>Skipping target "GenerateTargetFrameworkMonikerAttribute" because all output files are up-to-date with respect to the input files.
1>CoreCompile:
1>  C:\Program Files\Microsoft Visual Studio\2022\Community\MSBuild\Current\Bin\Roslyn\csc.exe /noconfig /nowarn:1701,1702,2008 /fullpaths /nostdlib+ /platform:AnyCPU /errorreport:prompt /warn:4 /define:DEBUG;TRACE /errorendlocation /preferreduilang:en-US /highentropyva+ /reference:C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\bin\Debug\ExampleDotNetLib.dll /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\mscorlib.dll" /reference:C:\Users\user\Documents\github\dotnet-mono-poc\packages\NUnit.3.13.3\lib\net45\nunit.framework.dll /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Core.dll" /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Data.dll" /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.dll" /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Xml.dll" /debug+ /debug:full /filealign:512 /optimize- /out:obj\Debug\ExampleDotNetLib.Tests.dll /subsystemversion:6.00 /target:library /utf8output /langversion:7.3 Class1Tests.cs Properties\AssemblyInfo.cs "obj\Debug\.NETFramework,Version=v4.8.AssemblyAttributes.cs"
1>  CompilerServer: server - server processed compilation - ExampleDotNetLib.Tests
1>_CopyFilesMarkedCopyLocal:
1>  Copying file from "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\bin\Debug\ExampleDotNetLib.dll" to "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\bin\Debug\ExampleDotNetLib.dll".
1>  Copying file from "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\bin\Debug\ExampleDotNetLib.pdb" to "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\bin\Debug\ExampleDotNetLib.pdb".
1>  Touching "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\obj\Debug\ExampleD.E978BF22.Up2Date".
1>CopyFilesToOutputDirectory:
1>  Copying file from "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\obj\Debug\ExampleDotNetLib.Tests.dll" to "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\bin\Debug\ExampleDotNetLib.Tests.dll".
1>  ExampleDotNetLib.Tests -> C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\bin\Debug\ExampleDotNetLib.Tests.dll
1>  Copying file from "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\obj\Debug\ExampleDotNetLib.Tests.pdb" to "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests\bin\Debug\ExampleDotNetLib.Tests.pdb".
1>RunTests:
1>  mono ../packages/NUnit.ConsoleRunner.3.10.0/tools/nunit3-console.exe bin/Debug/ExampleDotNetLib.Tests.dll
1>  NUnit Console Runner 3.10.0 (.NET 2.0)
1>  Copyright (c) 2019 Charlie Poole, Rob Prouse
1>  lunes, 2 de diciembre de 2024 15:22:17
1>  
1>  Runtime Environment
1>     OS Version: Microsoft Windows NT 6.2.9200.0
1>    CLR Version: 4.0.30319.42000
1>  
1>  Test Files
1>      bin/Debug/ExampleDotNetLib.Tests.dll
1>  
1>  
1>  Run Settings
1>      DisposeRunners: True
1>      WorkDirectory: C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib.Tests
1>      ImageRuntimeVersion: 4.0.30319
1>      ImageTargetFrameworkName: .NETFramework,Version=v4.8
1>      ImageRequiresX86: False
1>      ImageRequiresDefaultAppDomainAssemblyResolver: False
1>      NumberOfTestWorkers: 4
1>  
1>  Test Run Summary
1>    Overall result: Passed
1>    Test Count: 2, Passed: 2, Failed: 0, Warnings: 0, Inconclusive: 0, Skipped: 0
1>    Start time: 2024-12-02 14:22:19Z
1>      End time: 2024-12-02 14:22:20Z
1>      Duration: 1.450 seconds
1>  
1>  Results (nunit3) saved as TestResult.xml
1>
1>Build succeeded.
1>    0 Warning(s)
1>    0 Error(s)
1>
1>Time Elapsed 00:00:04.90
========== Build: 1 succeeded, 0 failed, 1 up-to-date, 0 skipped ==========
========== Build completed at 15:22 and took 05,050 seconds ==========
```
