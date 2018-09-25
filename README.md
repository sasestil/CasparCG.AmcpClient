![alt text](https://ci.appveyor.com/api/projects/status/github/stilsoft/CasparCG.AmcpClient?svg=true&retina=true)

# CasparCG AmcpClient
CasparCG AmcpClient is .NET library for communication with [CasparCG Server](https://github.com/CasparCG/Server) via [AMCP protocol](http://casparcg.com/wiki/CasparCG_2.1_AMCP_Protocol).

# Features
* Full Async commands (async/await support for non-blocking UI).
* Executing multiple commands asynchronously (thanks to new CasparCG REQ/RES command).
* Command parameters validation.
* Parsing command response.
* All commands are with proper return data.

# Examples
You can find example project in the source code ([AmcpClientExample](https://github.com/StilSoft/CasparCG.AmcpClient/tree/master/AmcpClientExample) project).

# License
CasparCG AmcpClient is distributed under the MIT License, see [LICENSE](LICENSE?raw=true) for details.

# Acknowledgements
Many thanks for [CasparCG Server](https://github.com/CasparCG/Server) project and contributors.

# Important notice
**_Currently support only AMCP 2.1 protocol._**

**_Almost all commands are fully implemented (acording to [AMCP protocol](http://casparcg.com/wiki/CasparCG_2.1_AMCP_Protocol) specification) but still missing some functions that are not listed in specification._**
