---
layout: game
title: "MECHADOOM"
order: 30
summary: "圧倒的な敵の包囲網を破壊する爽快感と戦略性を描く、BitSummit GameJamゲームデザイン賞受賞 3Dメカアクション"
tags: [Unity, C#, 3D Action, Team Dev]
thumbnail: "assets/images/games/MECHADOOM_thumbnail.png"
screenshot_base: "assets/images/games/MECHADOOM_"
screenshot_count: 7
screenshot_ext: ".png"
primary_url: "https://bitsummit-gamejam.itch.io/mechadoom"
primary_label: "itch.ioでダウンロード"
---

## 概要
BitSummit GameJamにて制作した3Dメカアクションゲーム。東京の学生混成チーム（6名）で開発を行い、**ゲームデザイン賞(ゲームジャム内)**を受賞しました。

## 技術的アプローチ
* **群衆AIの制御アルゴリズム（包囲体験の構築）**
  すべての敵キャラクターが単純に最短距離でプレイヤーを追従すると、敵が一箇所に重なって塊になってしまい、アクションとしての見栄えや難易度の破綻が発生します。
  本作品では、先行作品（『エルデンリング』や『バイオハザード』シリーズなど）の群衆・空間制御手法を研究。周囲に散開して隙を伺うAI、プレイヤーの移動先を先回りするAIなど、複数の自律分散アルゴリズムを実装することで、敵が一塊にならずにプレイヤーを美しく包囲するスリリングな戦闘体験を創出しました。

## 課題解決（Learning & Feedback）
企画・実装の大部分を担当。チーム開発特有のコミュニケーションの難しさを経験しつつ、それを乗り越えて受賞できたことは大きな自信になりました。
企画においても、GameJamのテーマであった「OverPower」に沿った、プレイヤーに「圧倒的な力」と「その代償となるリスク」を与える、優れたリスクとリターンのある企画ができたと思います。ただ、短いゲームジャム内での難易度調整と手触りの微調整には課題が残り、調整工程の重要性を痛感しました。
