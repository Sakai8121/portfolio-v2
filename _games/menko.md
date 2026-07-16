---
layout: game
title: "MenkoBattle"
order: 140
summary: "アナログ玩具のダイナミックな「叩きつけ」の体験をデジタルに翻訳する、初めての3D対戦ゲーム"
tags: [Unity, C#, 3D, Local Multiplayer]
thumbnail: "assets/images/games/MenkoBattle_thumbnail.png"
screenshot_base: "assets/images/games/MenkoBattle_"
screenshot_count: 7
screenshot_ext: ".png"
primary_url: "https://unityroom.com/games/menkobattle"
primary_label: "Unityroomでプレイ"
---

## 概要
自身初となる3Dゲーム制作プロジェクト。「デジタルめんこ」での読み合いをコンセプトにした、2人ローカル対戦およびCOM戦を実装した対戦アクションゲームです。

## 技術的アプローチ
* **初めての3Dゲーム開発と対戦COMの実装**
  空間的な位置関係（法線、角度）を考慮した、叩きつけた際の衝突判定の実装。また、複数の異なるキャラクター属性やスキルパラメータをC#でクラス定義し、プレイヤーの動きに簡易的に応じるCOM対戦ロジックを実装しました。

## 課題解決（Learning & Feedback）
当時ソーシャルゲームにはまっていたことから、「多彩な属性や能力を持つキャラクター同士の読み合い」を軸にゲームを制作しました。
しかし、体験した方から「めんこを地面に叩きつけるというダイナミックなアナログ体験が、ボタン操作や単純なマウス入力ではうまく脳内に翻訳されない」というフィードバックをいただきました。当時はどのように改善すれば良いか悩みましたが、これがのちの開発で「入力インターフェースとゲーム内フィードバック（エフェクト、サウンド、画面揺れ）を結びつける、ゲームの手触りへの深いこだわり」を意識する大きなきっかけとなりました。
