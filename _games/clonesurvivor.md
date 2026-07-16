---
layout: game
title: "分身サバイバー"
order: 100
summary: "「分身＝攻撃力増加×被弾範囲拡大」のリスク・リターン設計からゲームデザインの本質に迫った意欲作"
tags: [Unity, C#]
thumbnail: "assets/images/games/clonesurvivor_thumbnail.png"
screenshot_base: "assets/images/games/CloneSurvivor_"
screenshot_count: 0
primary_url: "https://unityroom.com/games/clone_survivor"
primary_label: "Unityroomでプレイ"
---

## 概要
サバイバル系ゲームにどのような追加要素があったら面白いかを考え、1週間（Unity1Week「もうひとつ」）で制作した作品です。

## 技術的アプローチ
* **リスクリターンと体験のジレンマの設計**
  「プレイヤーを分身させるほど攻撃力が高くなるが、分身するほど当たり判定が大きくなり被弾確率が高くなる」という、明確なジレンマを持たせるゲームメカニクスを構築しました。

## 課題解決（Learning & Feedback）
リリース後、リスクリターンの意思決定のタイミングがプレイヤーに伝わりにくいという課題が浮き彫りになりました。
敵が多すぎる中で「いつ、どのタイミングで増やすのが最適か」の戦略性を欠いていたこと、また敵を倒した際の見返り（報酬）の期待感が分かりづらかったことが原因と分析。ボス戦のようなゲーム展開のメリハリを意識したフェーズ変化や、ビジュアル表現による期待値の強調設計など、のちの開発で「プレイヤーの認知を動かす」レベルデザインの視点を学ぶきっかけとなった大切な失敗ケーススタディです。
