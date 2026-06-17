### Note Only For Me
Don't delete this until June 18, 2027.
It is being used for reporting issue!

### Tools
`dotnet --version` : 10.0.301
`ng version` : 22.0.0
`npm --version` : 11.16.0
`node --version` : 24.16.0
Operating System : Win32 x64 (Windows 10)

### Actions
```
E:\myfolder>aspire init
Select AppHost Language

Choose the programming language for your Aspire AppHost.
This selection will be saved for future use.
Which language would you like to use? C# (.NET)
📦 Created or updated NuGet.config in the project directory with   required package sources.                                    
✅ Created fullbench-dll.AppHost/

Would you like to configure AI agent environments for this project? [Y/n]: n
```
By selecting C# and answering `n` for AI, 
it produces ONLY `aspire.config.json`:
```json
{
  "appHost": {
    "language": "csharp"
  }
}
```

No `AppHost.cs` generated.