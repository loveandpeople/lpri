<h1 align="center">
  <br>
  <a href="https://docs.dag-lp.com/docs/node-software/0.1/iri/introduction/overview"><img src="LPRI.png"></a>
</h1>

<h2 align="center">The official node software that runs on the LP Mainnet and Devnet</h2>

<p align="center">
    <a href="#" style="text-decoration:none;">
    <img src="#" alt="Developer documentation portal">
</p>
<p align="center">
  <a href="#" style="text-decoration:none;"><img src="https://img.shields.io/badge/Discord-9cf.svg?logo=discord" alt="Discord"></a>
    <a href="#" style="text-decoration:none;"><img src="https://img.shields.io/badge/StackExchange-9cf.svg?logo=stackexchange" alt="StackExchange"></a>
    <a href="#" style="text-decoration:none;"><img src="https://img.shields.io/github/license/iotaledger/iri.svg" alt="GPL-3.0 license"></a>
    <a href="#" style="text-decoration:none;"><img src="https://api.codacy.com/project/badge/Grade/dba5b7ae42024718893991e767390135"></a>
    <a href="#" style="text-decoration:none;"><img src="https://travis-ci.org/iotaledger/iri.svg?branch=dev" alt="Build status"></a>
</p>
      
<p align="center">
  <a href="#about">About</a> ◈
  <a href="#prerequisites">Prerequisites</a> ◈
  <a href="#installation">Installation</a> ◈
  <a href="#getting-started">Getting started</a> ◈
  <a href="#api-reference">API reference</a> ◈
  <a href="#supporting-the-project">Supporting the project</a> ◈
  <a href="#joining-the-discussion">Joining the discussion</a> 
</p>

---

## About

The LPRI (LP reference implementation) is open-source Java software that runs on the LP Mainnet as well as the Devnet. This software defines the current LP protocol, which allows nodes to do the following:

- Validate transactions
- Store valid transactions in a ledger
- Allow clients to interact with the them through a an HTTP API

This is beta software, so there may be performance and stability issues.
Please report any issues in our [issue tracker](https://github.com/loveandpeople/lpri/issues/new).

## Prerequisites

To run LPRI, you need the following:

- 4GB RAM
- 64-bit processor
- A public IP address that's either static or connected to a dynamic DNS service such as [duckdns.org](https://www.duckdns.org)
- [Java](https://openjdk.java.net/install/)
- [Maven](https://maven.apache.org/what-is-maven.html)
- Ports 15600 and 14265 must be open

## Installation

You can do one of the following:

- Download the pre-built Java file
- Compile the Java file yourself

Or, if you use Docker, you can [run the pre-built Docker image](https://docs.dag-lp.com/docs/node-software/0.1/iri/how-to-guides/install-iri#run-iri-in-a-docker-container)

### Downloading the pre-built Java file

After every release, we upload a pre-built Java file onto the [GitHub Releases page](https://github.com/loveandpeople/lpri/releases).

You can simply download the latest `.jar` file.

### Compiling the Java file

To compile the Java file yourself, do the following on a Linux operating system:

```bash
git clone https://github.com/loveandpeople/lpri
cd lpri
mvn clean package
```

Your `.jar` file is in the `target` directory.

# Getting started

For instructions on running LPRI, see the [documentation portal](https://docs.dag-lp.com/docs/node-software/0.1/iri/how-to-guides/install-iri).

## API reference

For an API reference, see the [documentation portal](https://docs.dag-lp.com/docs/node-software/0.1/iri/references/api-reference).

## Supporting the project

If you want to contribute to LPRI, consider posting a [bug report](https://github.com/loveandpeople/lpri/issues/new), [feature request](https://github.com/loveandpeople/lpri/issues/new) or a [pull request](https://github.com/loveandpeople/lpri/pulls/). 

Please read the following before contributing:

- [Contributing guidelines](CONTRIBUTING.md)
- [Code styleguide](STYLEGUIDE.md)
- [Responsible disclosure policy](SECURITY.MD)

## Joining the discussion

If you want to get involved in the community, need help with getting set up, have any issues related to LPRI, or just want to discuss LP, Distributed Registry Technology (DRT) and IoT with other people, feel free to join our [Discord](https://discord.dag-lp.com/).

## Special thanks

### ![alt text](https://www.yourkit.com/images/yklogo.png)

YourKit supports open-source projects with its full-featured Java Profiler.
YourKit, LLC is the creator of <a href="https://www.yourkit.com/java/profiler/">YourKit Java Profiler</a> and <a href="https://www.yourkit.com/.net/profiler/">YourKit .NET Profiler</a>, innovative and intelligent tools for profiling Java and .NET applications.
