<p align="center">
  <img width="70%" src="https://user-images.githubusercontent.com/98148217/236020704-b931f1b0-3c4b-4bd3-95fb-f0c22e40a093.png">
</p>

<p align="center">
  <a href="https://discord.gg/t8WMq5JKaK">
    <img src="https://dcbadge.vercel.app/api/server/NQY28YSVAb?style=flat">
  </a>
  <a href="https://github.com/LExteamz/LInjector/releases">
    <img src="https://img.shields.io/github/v/release/LExteamz/LInjector?color=success&label=version">
  </a>
  <a href="https://github.com/LExteamz/LInjector/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/LExteamz/LInjector?color=blue">
  </a>
</p>

<h3 align="center">⚡ Next-Gen Lua Execution Environment | 🛠️ Developer-First Design</h3>

<div align="center">
  <img src="https://github.com/LExteamz/LInjector/assets/98148217/ec726092-c282-4570-80dd-d7e061215cb0" width="45%">
  <img src="https://github.com/LExteamz/LInjector/assets/147359654/a32c944e-5240-4d35-bfeb-786e4918860a" width="45%">
</div>

## 🌟 Features That Shine
- 🔓 **100% Open Source** - Full transparency with MIT License
- 🛡️ **Security First** - Community-vetted codebase
- ✨ **VS Code Power** - Monaco editor integration
- 🧩 **Modular Architecture** - Easy to extend and customize
- 📦 **DLL Flexibility** - Bring your own injection method

```csharp
// Example of clean architecture
public class ScriptExecutor
{
    private readonly IInjectionService _injector;
    
    public ScriptExecutor(IInjectionService injector)
    {
        _injector = injector;
    }
    
    public void Execute(string script)
    {
        if(ValidateScript(script))
        {
            _injector.Run(script);
        }
    }
}
