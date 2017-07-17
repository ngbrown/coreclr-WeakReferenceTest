This demonstrates https://github.com/dotnet/coreclr/issues/12847

For .NET Framework, run:

```
dotnet test -f net461
```


For .NET Core 2.0, run:

```
dotnet test -f netcoreapp2.0
```

This was tested with:

```
.NET Command Line Tools (2.0.0-preview2-006497)

Product Information:
 Version:            2.0.0-preview2-006497
 Commit SHA-1 hash:  06a2093335

Runtime Environment:
 OS Name:     Windows
 OS Version:  10.0.15063
 OS Platform: Windows
 RID:         win10-x64
 Base Path:   C:\Program Files\dotnet\sdk\2.0.0-preview2-006497\

Microsoft .NET Core Shared Framework Host

  Version  : 2.0.0-preview2-25407-01
  Build    : 40c565230930ead58a50719c0ec799df77bddee9
```