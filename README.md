---
marp: true
paginate: true
---

# アジャイル開発概論

WebDINO Japan エンジニア
[渡邉浩平](https://github.com/kou029w)
![w:200](https://github.com/kou029w.png)

---

## 世界は不確実

![bg right:62% 将来ほど予報円が大きく予測困難](https://www.jma.go.jp/jma/kishou/know/typhoon/7-1-1.png)
<!-- _footer: 図の出典: 気象庁 https://www.jma.go.jp/jma/kishou/know/typhoon/7-1.html -->

将来ほど予測困難

---

## ソフトウェア開発は不確実

スケジュールは予測困難

![不確実性コーン](https://i.gyazo.com/200d8e3772754e6b9f0a17927229cc2b.png)
<!-- _footer: 図の出典: 不確実性コーン - Mike Cohn, 2009 「アジャイルな見積りと計画づくり」 -->

---

## ソフトウェア開発の目的と現実

開発したサービスによって実際に利用者が便利になり役に立つということ

しかし、現実は不確実

- 利用者が何をほしいか不明瞭
- コストと納期の見積もりは困難
- 需要は予測困難

作るのに時間がかかりすぎてたくさんコストがかかってしまったり、利用者が欲しいものと異なっていたりということは、なるべく避けなければならない

---

## さまざまな方法論

![h:580](https://i.gyazo.com/bef43058445b8a7235ef28e1b16a7ebc.png)

<!-- _footer: http://agilelion.com/agile-kanban-cafe/agile-and-lean-influences-where-did-kanban-scrum-scrumban-come-from -->

---

## アジャイルとは

ウォーターフォール型の重たい方法論からの脱却が背景
アジャイルとは現実に寄り添った変化への対応の機会をすばやく取り入れる考え方

> 私たちは、ソフトウェア開発の実践あるいは実践の手助けをする活動を通じて、よりよい開発方法を見つけ出そうとしている。
> この活動を通して、私たちは以下の価値にたどり着いた。
> プロセスやツールよりも**個人と対話**を
> 包括的なドキュメントよりも**動くソフトウェア**を
> 契約交渉よりも**顧客との協調**を
> 計画に従うことよりも**変化への対応**を
> 価値とする。すなわち、左記のことがらに価値があることを認めながらも、私たちは右記のことがらにより価値をおく。

<!--
_footer: 引用元: Kent Beck et al. (2001) [アジャイルソフトウェア開発宣言](https://agilemanifesto.org/iso/ja/manifesto.html)
-->

---

## 何でないか

- 特定のテクニックや儀式ではない
- ソフトウェア開発の真理ではない

---

## 「なぜアジャイルか」

現代のソフトウェア開発においてこの問い自体もはや重要ではない

なぜなら

- 技術の進展とともに、すばやく変化に対応し続けるアジャイルの考え方は普及
- リリースして終了というウォーターフォール型のプロジェクトは衰退

---

## ここまでの話

- 現実は不確実
- ソフトウェア開発は価値を提供することが目的
- アジャイルとは変化への対応の機会をすばやく取り入れる考え方

---

## アジャイルをもっと知る

開発の現場で実践するためのヒント

---

## 代表的な儀式の紹介

- スクラム
- カンバン

実践の方法はチームによって異なる
大切なのは現実の問題に向き合い価値を提供するということ

---

## スクラム

10人以下のチームの自己管理のための代表的なフレームワーク

![bg right:40% fit スクラムの図](https://i.gyazo.com/80bf708078dfa7baeacdf8d981a79a81.png)


[スクラムガイド](https://scrummaster.jp/scrum-guide)によって定義されるスクラムの3本柱と呼ばれる透明性・検査・適応という価値観はアジャイル開発において重要な概念

開発範囲はチームのベストエフォート

対応可能な分量ですばやくリリースを続ける

スプリントと呼ばれる制限期間の中で日々の開発を続ける

---

## カンバン

作業項目あたりの提供するまでの期間の可視化

![bg right:40% fit](https://image.slidesharecdn.com/predictabilitymeasurementinkanbanmunich-140118163930-phpapp02/95/key-note-lean-kanban-central-europe-2011-predictability-measurement-with-kanban-1-638.jpg)

<!--
_footer: 画像の出典: David J. Anderson, 2011 https://www.slideshare.net/agilemanager/key-note-lean-kanban-central-europe-2011-predictability-measurement-in-kanban
-->

提供するまでの期間はチームのベストエフォート

対応可能な分量ですばやくリリースを続ける

仕掛(WIP)の制限を行うことで一定の作業項目数の中で日々の開発を続ける

---

## まとめ

- ソフトウェア開発は不確実
- アジャイルは現実に寄り添った変化への対応の機会をすばやく取り入れる考え方
- 代表的な儀式の紹介

やっていきましょう 💪

---

## 後付

---

## 話していないこと

- トヨタ式生産手法
- リーン
- 大規模アジャイル
- XP
- CI/CD
- DevOps

---

## 知識を深めるための資料

- [Atlassianアジャイルコーチ](https://www.atlassian.com/ja/agile)
- [スクラムガイド](https://scrummaster.jp/scrum-guide)

---

## 歴史

- 1978年 大野耐一「トヨタ生産方式」
- 1986年 竹内弘高, 野中郁二郎「The New New Product Development Game」
- 1990年代 Jeff Sutherland, Ken Schwaber「Scrum」
- 1994年 The "Gang of Four", Erich Gamma et al.「Design Patterns」
- 1999年 Kent Beck「Extreme Programming」
- 2003年 Mary & Tom Poppendieck「Lean Software Development」
- 2005年 Steven G. Blank「The Four Steps to the Epiphany」
- 2010年 David J. Anderson「Kanban」
- 2011年 Eric Ries「Lean Startup」
