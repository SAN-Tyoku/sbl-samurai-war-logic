# SBL-WAR 算出ロジック仕様書

![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)
![Format](https://img.shields.io/badge/Format-LaTeX-green.svg)

## 概要

このプロジェクトは、プロ野球選手として入団から引退、そして次の世代へと野球人生を体験するオンラインシミュレーションゲーム「[ベースボールライフ](https://baseball-life.games/)」(BBL) の世界で生まれたものです。

BBLにおける有志による企画「SBL侍ジャパン」での選手表彰のために、リーグ特有の環境を反映した独自のWAR (Wins Above Replacement)算出ロジックが考案されました。

本リポジトリでは、その計算ロジックの理論的枠組みと数理モデルを記述した仕様書を管理しています。

## 公開ドキュメント

数式定義の厳密性を保つため、ドキュメントはLaTeX形式で記述されています。

* [ソースコード (TeX)](./main.tex)
* [ドキュメント（pdf）](https://github.com/SAN-Tyoku/sbl-samurai-war-logic/releases/latest/download/sbl_war_methodology.pdf)

> **注意**
> 本指標はSBLというシミュレーション環境に特化して調整されたものです。
> リーグのメタやゲームバランスを反映しているため、現実のプロ野球で用いられる一般的なWAR（fWAR/rWAR）とは、係数や一部の計算定義が異なります。

## ライセンス

本ドキュメントは、CC BY-NC-ND 4.0ライセンスの下で公開されています。
[![CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

© SAN-Chi Chokusou / SBL Samurai Japan Project