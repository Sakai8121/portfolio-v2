---
layout: game
title: "FlyShooting"
order: 120
summary: "3Dアクションゲームの基盤システムを一から自作した、技術指向の宇宙FPSシューティング"
tags: [Unity, C#, FPS System, 3D Modeling]
thumbnail: "assets/images/games/FlyShooting_thumbnail.png"
screenshot_base: "assets/images/games/FlyShooting_"
screenshot_count: 2
screenshot_ext: ".png"
primary_url: "https://unityroom.com/games/flyshooting"
primary_label: "Unityroomでプレイ"
---

## 概要
宇宙空間でのFPSシューティングゲームです。企画性よりも「FPSのシステムそのものをゲームエンジン依存ではなく、スクリプトで自作する」という純粋な技術的挑戦を主軸に置いたプロジェクトです。

## 技術的アプローチ
* **FPSコアエンジンの自作と3Dモデリング**
  FPS特有のカメラ制御（マウスによる視点回転）、射撃時におけるカメラシェイク（反動演出）、Raycastによる高速なヒット検知ロジックなどをスクリプトで一からC#実装。また、Blenderを用いて3Dモデルのアセット制作も行いました。

## 課題解決（Learning & Feedback）
市販のFPSゲームにおける「走る・狙う・撃つ」といった当たり前の操作感や気持ちよさが、いかに高度で複雑な微細パラメーター（エイム時の補正、画面のミリ単位のブレ、エフェクトのタイミング）の調整の集積によって成り立っているかを痛感しました。以降の開発における「ゲームの手触り、ミリ秒レベルの演出調整への執念」を宿す、自身の技術的原点となった作品です。
