```
Build started at 15:20...
  GET https://api.nuget.org/v3/vulnerabilities/index.json
  OK https://api.nuget.org/v3/vulnerabilities/index.json 324ms
  GET https://api.nuget.org/v3-vulnerabilities/2024.11.25.23.06.43/vulnerability.base.json
  GET https://api.nuget.org/v3-vulnerabilities/2024.11.26.11.06.45/2024.11.26.11.06.45/vulnerability.update.json
  OK https://api.nuget.org/v3-vulnerabilities/2024.11.25.23.06.43/vulnerability.base.json 882ms
  OK https://api.nuget.org/v3-vulnerabilities/2024.11.26.11.06.45/2024.11.26.11.06.45/vulnerability.update.json 992ms
1>------ Build started: Project: ExampleDotNetLib, Configuration: Debug Any CPU ------
1>Build started 02/12/2024 15:20:53.
1>GenerateTargetFrameworkMonikerAttribute:
1>Skipping target "GenerateTargetFrameworkMonikerAttribute" because all output files are up-to-date with respect to the input files.
1>CoreCompile:
1>  C:\Program Files\Microsoft Visual Studio\2022\Community\MSBuild\Current\Bin\Roslyn\csc.exe /noconfig /nowarn:1701,1702,2008 /fullpaths /nostdlib+ /platform:AnyCPU /errorreport:prompt /warn:4 /define:DEBUG;TRACE /errorendlocation /preferreduilang:en-US /highentropyva+ /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\mscorlib.dll" /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Core.dll" /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Data.dll" /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.dll" /reference:"C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Xml.dll" /debug+ /debug:full /filealign:512 /optimize- /out:obj\Debug\ExampleDotNetLib.dll /subsystemversion:6.00 /target:library /utf8output /langversion:7.3 Class1.cs Properties\AssemblyInfo.cs "obj\Debug\.NETFramework,Version=v4.8.AssemblyAttributes.cs"
1>  CompilerServer: server - server processed compilation - ExampleDotNetLib
1>CopyFilesToOutputDirectory:
1>  Copying file from "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\obj\Debug\ExampleDotNetLib.dll" to "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\bin\Debug\ExampleDotNetLib.dll".
1>  ExampleDotNetLib -> C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\bin\Debug\ExampleDotNetLib.dll
1>  Copying file from "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\obj\Debug\ExampleDotNetLib.pdb" to "C:\Users\user\Documents\github\dotnet-mono-poc\ExampleDotNetLib\bin\Debug\ExampleDotNetLib.pdb".
1>
1>Build succeeded.
1>    0 Warning(s)
1>    0 Error(s)
1>
1>Time Elapsed 00:00:00.69
========== Build: 1 succeeded, 0 failed, 0 up-to-date, 0 skipped ==========
========== Build completed at 15:20 and took 04,689 seconds ==========
```
