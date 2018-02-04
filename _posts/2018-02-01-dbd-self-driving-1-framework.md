---
layout: post
title:  "[MYOA積み重ね]自動走行 (1) 技術フレームワーク"
date:   2018-02-01 17:17:00 +0800
categories: 
---

シリーズの最初の記事として、オープンな自動走行プラットフォーム－Apolloから、自動走行技術のフレームワークを望んでみます。

# Apollo技術フレームワークのレイヤー
下から上に、技術の基本とハイレベルの順で、下記の四つのレイヤーがあります。
* Reference Vehicle Platform 
* Reference Hardware Platform
* Open Software Platform
* Cloud Service Platform

つまり、車、ハードウェア、ソフトウェア、クラウドの四つのレイヤー。
ちょっと興味深いにのはソフトレイヤーには「オープン」の言葉、車とハードウェアレイヤーには「レファレンス」の言葉があります。つまり、手には入ります。これで自動走行の扉があけてくれました。

# Reference Vehicle Platform
Reference Vehicle Platform は車のプラットフォームです。

# Reference Hardware Platform
Reference Hardware Platform
* Computing Unit 
* GPS/IMU 
* Camera 
* LiDAR
* Radar
* HMI Device 
* Black Box 

# Open Software Platform
Open Software Platform 
* RTOS 
* Runtime Framework 
* Map Engine 
* Localization 
* Perception 
* Planning 
* Control 
* End-to-End
* HMI

# Cloud Service Platform
Cloud Service Platform
* HD Map 
* Simulation 
* Data Platform 
* Security 
* OTA 
* DuerOS

具体的なモジュールはこれからの記事で解説します。

リファレンス：
* [Apollo（オフィシャルサイト）](http://apollo.auto/)
* [ApolloAuto/apollo（Github）](http://github.com/ApolloAuto/apollo)

