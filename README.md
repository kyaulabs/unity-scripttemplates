# <img src=".github/media/unity.svg" style="height:48px;vertical-align:text-bottom;"/> Unity - ScriptTemplates
[https://kyaulabs.com/](https://kyaulabs.com/)

[![Contributor Covenant](https://img.shields.io/badge/contributor%20covenant-2.1-4baaaa.svg?logo=open-source-initiative&logoColor=4baaaa)](CODE_OF_CONDUCT.md) &nbsp; [![Conventional Commits](https://img.shields.io/badge/conventional%20commits-1.0.0-fe5196?style=flat&logo=conventionalcommits)](https://www.conventionalcommits.org/en/v1.0.0/) &nbsp; [![GitHub](https://img.shields.io/github/license/kyaulabs/unity-scripttemplates?logo=creativecommons)](LICENSE) &nbsp; [![Gitleaks](https://img.shields.io/badge/protected%20by-gitleaks-blue?logo=git&logoColor=seagreen&color=seagreen)](https://github.com/zricethezav/gitleaks)  
[![Semantic Versioning](https://img.shields.io/github/v/release/kyaulabs/unity-scripttemplates?include_prereleases&logo=semver&sort=semver)](https://semver.org) &nbsp; [![Discord](https://img.shields.io/discord/88713030895943680?logo=discord&color=blue&logoColor=white)](https://discord.gg/DSvUNYm)

# Disclaimer

* [About](#about)
* [Usage](#usage)
  * [Format](#format)
  * [Variables](#variables)
* [Attribution](#attribution)

# About

The Unity Editor uses `ScriptTemplates` as the templates for new file creation, all of these can be accessed by right-clicking in the `Project` window and selecting `Create`.

# Usage

To utilize these templates over the defaults locate the following.

Location: `%ProgramFiles%\Unity\Hub\Editor\20xx.x.xxfx\Editor\Data\Resources\ScriptTemplates`\

```bash
cd %ProgramFiles%\Unity\Hub\Editor\20xx.x.xxfx\Editor\Data\Resources
rm -rf ScriptTemplates
git clone https://github.com/kyaulabs/unity-scripttemplates ScriptTemplates
```

## Format

All templates follow the same naming syntax:

```
81-C# Script__Enum-NewEnum.cs.txt
```

| 81 | C# Scripts | Enum | NewEnum | .cs |
| - | - | - | - | - |
| Menu Position | Menu Name | Menu Item | Default filename | File extension |

## Variables

There are a couple of variables that you are allowed to use inside of script templates.

* `#SCRIPTNAME#`: will be replaced with the name of the script
* `#NOTRIM#`: will make it so the white-space of the current line is not trimmed
* `#ROOTNAMESPACEBEGIN#` and `#ROOTNAMESPACEEND#`: will wrap something with the default namespace

# Attribution
