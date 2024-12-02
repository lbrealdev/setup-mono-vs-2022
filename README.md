# setup-mono-vs-2022

Use mono in Visual Studio 2022

```
C:\Program Files\Mono\bin\mono.exe
```

Set environment variable at `User` level:
```powershell
[Environment]::SetEnvironmentVariable("PATH", $env:PATH + ";C:\Program Files\Mono\bin", "User")
```

Set environment variable at `Machine` level:
```powershell
[Environment]::SetEnvironmentVariable("PATH", $env:PATH + ";C:\Program Files\Mono\bin", "Machine")
```
