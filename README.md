## Installation
1. The package is available on the [openupm registry](https://openupm.com). You can install it via [openupm-cli](https://github.com/openupm/openupm-cli).
```
openupm add net.tnrd.lidgren
```

2. Installing through a [Unity Package](http://package-installer.glitch.me/v1/installer/package.openupm.com/net.tnrd.lidgren?registry=https://package.openupm.com) created by the [Package Installer Creator](https://package-installer.glitch.me) from [Needle](https://needle.tools)

[<img src="https://img.shields.io/badge/-Download-success?style=for-the-badge"/>](http://package-installer.glitch.me/v1/installer/package.openupm.com/net.tnrd.lidgren?registry=https://package.openupm.com)

3. Installing from git through the package manager by clicking the + icon and then selecting 'Add package from git URL...'



and using the following url: `https://github.com/Thundernerd/Unity3D-Lidgren.git`


4. Installing from git by adding the following line to your manifest.json
```
"net.tnrd.lidgren": "https://github.com/Thundernerd/Unity3D-Lidgren.git"
```

Original readme below this line
---

**Note! Not actively developed any more; only accepting trivial or minor bug fixes.**

# Lidgren.Network ![](https://api.travis-ci.org/RevoluPowered/lidgren-network-gen3.svg?branch=master)
Lidgren.Network is a networking library for .NET framework, which uses a single UDP socket to deliver a simple API for connecting a client to a server, reading and sending messages.

This has been updated for use with Unity3D, feel free to send PRs for other bugs fixes.
To use this in Unity3D just enable the experimental .NET framework.
you can do this in Edit -> Project Settings -> Player -> Other Settings -> Api Compatibility Level -> .NET 4.6

Platforms supported:
- Linux
- Mac
- OSX

Platforms/Toolchains which need testing:
- Android
- iPhone
- Xamarin

Tested in:
- Mono (alpha and beta)
- .NET 4.6
- Unity 2017.1 -> 2018.1.

Future Roadmap:
- Update to latest .NET 4.6
- Investigate officially supporting .NET Core.
- Improve test suite so that tests are run on all platforms we support, for each release.
