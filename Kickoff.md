---
# スライドのタイトル、ファイルの情報として記録されます。
title: キックオフ資料
# ファイルの情報として記録されます。
description: キックオフ資料
# テーマ設定 default gaia uncover
theme: "confidential"
# ページ番号を表示する
paginate: true
# ヘッダー文字列
header: "社外秘"
# フッター文字列
footer: "© 2024 ktama"
# サイズ指定
size: "16:9"
# marpの使用
marp: true
---
<!-- _class: titlepage -->
# キックオフ資料

`@ktama`

---
<!-- _class: toc -->
## 目次<!-- omit in toc -->
- [キックオフ資料](#キックオフ資料)
  - [プロジェクトの目的](#プロジェクトの目的)
  - [システムの概要](#システムの概要)
  - [プロジェクトの日程](#プロジェクトの日程)
  - [プロジェクトの体制](#プロジェクトの体制)
  - [プロジェクトの管理方法](#プロジェクトの管理方法)
  - [レポーティング](#レポーティング)
  - [各種会議体](#各種会議体)
  - [記載例1](#記載例1)
  - [記載例2](#記載例2)

---
## プロジェクトの目的

---
## システムの概要

---
## プロジェクトの日程

<div class="mermaid" style="font-size: 80%; text-align: center;" >
gantt
    title A Gantt Diagram
    dateFormat YYYY-MM-DD
    section Section
        A task          :a1, 2014-01-01, 30d
        Another task    :after a1, 20d
    section Another
        Task in Another :2014-01-12, 12d
        another task    :24d
</div>
<!-- mermaid.js -->
<script src="https://unpkg.com/mermaid@8.1.0/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

---
## プロジェクトの体制

<div class="mermaid" style="font-size: 50%; text-align: center;" >
graph TB
  A[Aさん]-->B[Bさん]
  B-->C[Cさん]
  C-->D[Dさん]
  C-->E[Eさん]
  C-->F[Fさん]
</div>
<!-- mermaid.js -->
<script src="https://unpkg.com/mermaid@8.1.0/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

---
## プロジェクトの管理方法

---
## レポーティング

---
## 各種会議体


---
## 記載例1

_Markdown_ の __記法__ により *斜体* や **太字** ~~打ち消し~~ 

> blockquote
> 引用

- 1つめ
- 2つめ
1. 1つめ
2. 2つめ

---
## 記載例2

| left | center  |   right |
| :--- | :-----: | ------: |
| odd  | 200,000 | 300,000 |
| even | 123,456 |   2,000 |
| odd  | 999,999 | -50,000 |

!["代替テキスト"](./images/Sample.svg)

---
<!-- _class: lastpage -->
## 最終ページ<!-- omit in toc -->


