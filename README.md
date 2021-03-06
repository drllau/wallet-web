# Ethereum Wallet (Web)

<p align="center">
   	<a href="https://travis-ci.com/june111/wallet-web" rel="nofollow">
    	<img src="https://travis-ci.com/june111/wallet-web.svg?branch=master" alt="Build Status" />
  	</a>
	<a href="https://github.com/vuejs/vue">
    	<img src="https://img.shields.io/badge/vue-2.5.21-brightgreen.svg" alt="vue" />
  	</a>
  	<a href="https://github.com/ElemeFE/element">
    	<img src="https://img.shields.io/badge/element--ui-2.4.10-brightgreen.svg" alt="element-ui" />
  	</a>
	<a href="https://codebeat.co/projects/github-com-june111-wallet-web-master">
		<img src="https://codebeat.co/badges/a10a9b6b-6ac0-42e5-a8de-64d4ac7062c5" alt="codebeat badge" />
	</a>
</p>

English | [简体中文](./README.zh-CN.md)

## Introduction

A web version of the HD (Hierarchical Deterministic) wallet. You can back up or import your wallet with mnemonics, private keys, keystores. It can also be used to transfer and receipt on account.

Live version available at [http://blog.junezhu.top/wallet-web/](http://blog.junezhu.top/wallet-web/)

## Features

* BIP32 Hierarchical deterministic (HD) address generation 
* Mnemonic (BIP39) support for wallet backups
* Export a private key or keystore to backup
* Importing a mnemonic phrase, private key or keystore to import the address 
* Device-based security: all private keys are stored locally, not in the cloud
* Send and receive payments
* Offline qrcode creator
* Customizable wallet naming

## Author

**June** -> [email](mailto:ru-q-ur@163.com)


## Getting started
```bash
# Installing
npm install
# Compiles and hot-reloads for development
npm run dev
```
App will be running at: http://localhost:8080/wallet-web/ 

## Build 
```bash
npm run build
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


