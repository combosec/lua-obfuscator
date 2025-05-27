# 📜 ComboSec
[![Discord](https://raw.githubusercontent.com/combosec/lua-obfuscator/refs/heads/main/1000048093-removebg-preview.png)](https://discord.gg/6cpCsgRctM)
## ComboSec is a *FREE* Lua obfuscator that made in 2025

# Run in
Lua 5.1
Lua 5.2
Lua 5.3
Lua 5.3.5
Luau (executor) 
Luau (Roblox Studio) 

Prometheus has an official [Discord server](https://discord.gg/U8h4d4Rf64).

## Installation
To install Prometheus, simply clone the Github Repository using:

```batch
git clone https://github.com/levno-710/Prometheus.git
```

Alternatively you can download the Sources [here](https://github.com/prometheus-lua/Prometheus/archive/refs/heads/master.zip).

Prometheus also Requires LuaJIT or Lua51 in order to work. The Lua51 binaries can be downloaded [here](https://sourceforge.net/projects/luabinaries/files/5.1.5/Tools%20Executables/).

## Usage
To quickly obfuscate a script:
```batch
lua ./cli.lua --preset Medium ./your_file.lua
```
When using the windows release:
```batch
prometheus.exe --preset Medium ./your_file.lua
```
For more advanced use cases see the [Documentation](https://levno-710.gitbook.io/prometheus/).
## Tests
To perform the Prometheus Tests, just run
```batch
lua ./tests.lua
```

## Building
Prometheus can currently only build on Windows.
It requires [srlua.exe](https://github.com/LuaDist/srlua) and [glue.exe](https://github.com/LuaDist/srlua) inside of the root directory. If lua51 was linked dynamically, lua51.dll must also be present. Then Prometheus for Windows can be built using
```batch
build.bat
```
This creates a folder named build, that contains prometheus.exe as well as everything that is needed in order to run Prometheus.   
Then
```batch
prometheus.exe [options]
```
can be used instead of
```batch
lua ./cli.lua [options]
```

## License
This Project is Licensed under the GNU Affero General Public License v3.0. For more details, please refer to [LICENSE](https://github.com/levno-710/Prometheus/blob/master/LICENSE).
