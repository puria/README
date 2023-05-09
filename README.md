<div align="center">

# {project_name}

### {tagline}

</div>

<p align="center">
  <a href="https://dyne.org">
    <img src="https://files.dyne.org/software_by_dyne.png" width="170">
  </a>
</p>


---
<br><br>


## {project_name} Features

{screenshot}

# [LIVE DEMO](https://https://interfacer-gui-staging.dyne.org/)

<br>

<div id="toc">

### 🚩 Table of Contents

- [💾 Install](#-install)
- [🎮 Quick start](#-quick-start)
- [🚑 Community & support](#-community--support)
- [🐋 Docker](#-docker)
- [🐝 API](#-api)
- [🔧 Configuration](#-configuration)
- [📋 Testing](#-testing)
- [🐛 Troubleshooting & debugging](#-troubleshooting--debugging)
- [😍 Acknowledgements](#-acknowledgements)
- [👤 Contributing](#-contributing)
- [💼 License](#-license)

</div>

***
## 💾 Install
```pip install / yard add {project_name}```


**[🔝 back to top](#toc)**

***
## 🎮 Quick start

To start using {project_name} run the following command in the root folder

```bash
docker compose up
```

**[🔝 back to top](#toc)**

***
## 🚑 Community & support

**[📝 Documentation](#toc)** - Getting started and more.

**[🌱 Ecosystem](https://github.com/dyne/ecosystem)** - Plugins, resources, and more.

**[🚩 Issues](../../issues)** - Bugs end errors you encounter using {project_name}.

**[💬 Discussions](../../discussions)** - Get help, ask questions, request features, and discuss {project_name}.

**[[] Matrix](https://socials.dyne.org/matrix)** - Hanging out with the community.

**[🗣️ Discord](https://socials.dyne.org/discord)** - Hanging out with the community.

**[🪁 Telegram](https://socials.dyne.org/telegram)** - Hanging out with the community.

**[📖 Example](https://github.com/{project_name}/example)** - An example repository that uses {project_name}.

**[🔝 back to top](#toc)**

***
## 🐋 Docker

Please refer to [DOCKER PACKAGES](../../packages)


**[🔝 back to top](#toc)**

***
## 🐝 API

Available endpoints

### POST /token

Execute a transaction with some amount

**Parameters**

|          Name | Required |  Type   | Description       | 
| -------------:|:--------:|:-------:| ------------------|
|       `token` | required | string  | Type of token. Accepted values `idea` or `strength`  |
|       `amount`| required | number  | Transaction's token amount |
|       `owner` | required | ULID    | The ULID of the Agent's owner |
 
### GET /token/${request.token}/${request.owner}

Retrieves the actual value of the token type for the specified owner


**[🔝 back to top](#toc)**

***
## 🔧 Configuration

**[🔝 back to top](#toc)**

***

## 📋 Testing

**[🔝 back to top](#toc)**

***
## 🐛 Troubleshooting & debugging

**[🔝 back to top](#toc)**

***
## 😍 Acknowledgements

<a href="https://dyne.org">
  <img src="https://files.dyne.org/software_by_dyne.png" width="222">
</a>


Copyleft 🄯 2023 by [Dyne.org](https://www.dyne.org) foundation, Amsterdam

Designed, written and maintained by Puria Nafisi Azizi.

Special thanks to Mr. W. White for his special contributions.

**[🔝 back to top](#toc)**

***
## 👤 Contributing

Please first take a look at the [Dyne.org - Contributor License Agreement](CONTRIBUTING.md) then

1.  🔀 [FORK IT](../../fork)
2.  Create your feature branch `git checkout -b feature/branch`
3.  Commit your changes `git commit -am 'feat: New feature\ncloses #398'`
4.  Push to the branch `git push origin feature/branch`
5.  Create a new Pull Request `gh pr create -f`
6.  🙏 Thank you


**[🔝 back to top](#toc)**

***
## 💼 License
    {project_name} - {tagline}
    Copyleft 🄯 2023 Dyne.org foundation, Amsterdam

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as
    published by the Free Software Foundation, either version 3 of the
    License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

**[🔝 back to top](#toc)**
