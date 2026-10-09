<p align="center">
  <img src="assets/logo.png" width="128" height="128" alt="Vonode logo">
</p>

<h1 align="center">Vonode</h1>

<p align="center">
  <b>Keep your SIMs at home. Take your numbers anywhere.</b><br>
  Your SIMs on your own node, managed from your iPhone.
</p>

<p align="center">
  <a href="https://vonode.cc"><img alt="Website" src="https://img.shields.io/badge/website-vonode.cc-2a9468?style=flat-square"></a>
  <a href="https://github.com/vonode/vonode-releases/releases/latest"><img alt="Node releases" src="https://img.shields.io/badge/node-releases-2475c2?style=flat-square"></a>
  <img alt="App" src="https://img.shields.io/badge/app-iPhone%20%26%20iPad%20%C2%B7%20iOS%2017%2B-141b26?style=flat-square">
  <img alt="Self-hosted" src="https://img.shields.io/badge/self--hosted-Linux%20amd64-141b26?style=flat-square">
</p>

Vonode turns a Linux computer with cellular modules into a private node. The Vonode app for
iPhone and iPad reads and sends SMS, makes and answers calls, switches eSIM profiles and turns
on Wi-Fi calling, all through hardware you run yourself.

There is no Vonode cloud between you and your numbers: the app talks to your node directly over
encrypted SSH, and messages, call history and settings stay on the node you operate.

## Features

| Feature | What it does |
|---|---|
| **Messages** | Read and send SMS for every number on the node, with automatic junk sorting. |
| **Calls** | Make and answer calls through your node; incoming calls ring through CallKit, even in the background. |
| **Wi-Fi Calling** | Switch each SIM between cellular and Wi-Fi calling (VoWiFi) where your plan supports it. |
| **SIM and eSIM** | Download, switch, rename and delete eSIM profiles on a removable eUICC card. Physical SIMs work as they are. |
| **Check network** | A plain-language check of SIM, carrier, mobile data, SMS and calling service. |
| **Notifications** | SMS and call alerts through Apple push, with optional previews encrypted by your node. |
| **And the rest** | Carrier codes (USSD), automations, proxies, backups and moving to a new phone. |

## How it works

| The Vonode app | Your node | Your carrier |
|---|---|---|
| Messages, calls, numbers and settings in a native app for iPhone and iPad. | A 64-bit Linux computer running the Vonode node software, with up to five USB cellular modules. | Your own SIM and eSIM plans. Wi-Fi calling works where your carrier enables it on the plan. |

You pair the app by scanning a one-time QR code that your node shows. It is valid for five minutes,
and the app pins the node's SSH host key. A small relay run by VONODE LLC only delivers Apple
notifications.

## Get started

| Next step | Links |
|---|---|
| **Install the node** | [Install guide](https://vonode.cc/install/) · [Step-by-step guide](https://vonode.cc/install/guide/) |
| **Download** | [Latest node release](https://github.com/vonode/vonode-releases/releases/latest) · [Install instructions and wiki](https://github.com/vonode/vonode-releases) |
| **Check your hardware** | [Supported hardware](https://vonode.cc/hardware/) |
| **Get the app** | Free download on the App Store · iOS and iPadOS 17 or later · free plan available |
| **Support** | [support@vonode.cc](mailto:support@vonode.cc) · [vonode.cc/support](https://vonode.cc/support/) |

## About this account

This account publishes the Vonode node release files and documentation. Vonode is proprietary
software of VONODE LLC; its source code is not published here. The corresponding source of the
GPL and LGPL components the node includes is attached to every
[release](https://github.com/vonode/vonode-releases/releases).

Vonode is not an emergency service. Do not rely on it for emergency or life-safety communication.

<sub>© 2026 VONODE LLC · [Privacy](https://vonode.cc/privacy/) · [Terms](https://vonode.cc/terms/) · [vonode.cc](https://vonode.cc) · [简体中文](https://vonode.cc/zh-hans/) · [繁體中文](https://vonode.cc/zh-hant/)</sub>
