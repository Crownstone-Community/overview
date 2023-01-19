# Overview

## Crownstone Community

The Crownstone Community consists of volunteers who provide services around **smart home hardware based on the Nordic Semi nRF52 series** such as the Crownstone hardware. We will refer to this type of hardware as **Crownstone-compatible** hardware.

* The Crownstone Community runs a [discord server](https://discord.gg/TPYfMvV7bD) where support questions can be asked. Be friendly, the people within this community are volunteers.
* The software that can be run on Crownstone-compatible hardware is **open-source** and can be found at different repositories under [this community profile](https://github.com/Crownstone-Community/). Feel free to contribute yourselves!
* The software architecture has been designed in such way that Crownstone-compatible hardware can operate day to day without any connection to the internet. 
* The **Crownstone cloud** is maintained and operated by the Crownstone Community. The cloud is required for the exchange of security keys, inviting other people to your household, connecting to third-party servers, etc.
* A so-called [cloud installer](https://github.com/Crownstone-Community/cloud-installer) tool can be used to run your **own cloud**. In the app it is possible to change your cloud choice by setting custom addresses.
* The Crownstone apps for [Android](https://play.google.com/store/apps/details?id=rocks.crownstone.consumerapp) and [iOS](https://apps.apple.com/us/app/crownstone/id1136616106) will be maintained by the Crownstone Community.

## Software

An overview of the open-source software in the repositories of the Crownstone Community:

* The [Crownstone app](https://github.com/Crownstone-Community/crownstone-app) code for iOS and Android in React Native.
* The [Crownstone cloud](https://github.com/Crownstone-Community/crownstone-cloud) and [Crownstone cloud v2](https://github.com/Crownstone-Community/cloud-v2) code.
* The [nodejs](https://github.com/crownstone/crownstone-lib-nodejs-core) library (which contains references to cloud, uart, ble, and sse sublibraries).
* The [python](https://github.com/Crownstone-Community/crownstone-lib-python-core) library (which contains references to cloud, uart, ble, and sse sublibraries).
* The [Crownstone hub](https://github.com/Crownstone-Community/hub) code for a Raspberry PI type hub.
* The [microapp](https://github.com/Crownstone-Community/crownstone-microapp) code to be able to build microapps for Crownstone-compatible hardware.
* The [cloud installer](https://github.com/Crownstone-Community/cloud-installer) code to run your own private cloud.

See <https://github.com/orgs/Crownstone-Community/repositories> for more repositories.

## Contributions

Everyone can contribute to the software to the repositories in this community by sending a proper **pull request**. All contributions will be under the license agreements as stipulated per repository.

If you've general ideas or bug reports, these can be filed either at the individual code repositories, or in general at [issues](https://github.com/Crownstone-Community/overview/issues) in this repository.
