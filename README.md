# 基板データおよび作成方法置き場

Modbus接続用の簡易基板のデータ置き場です。プロジェクト全体の説明は [modbus_simple_system](https://github.com/KikuchiMakoto/modbus_simple_system) を参照してください。

## 発注先

シンプルな基板なので、[JLCPCB](https://jlcpcb.com/)・[P板.com](https://www.p-ban.com/) など、基板製造を請け負っている業者であればどこでも製造可能です。特定の業者に縛られる必要はありません。

## 組み立て・はんだ付け

基板の組み立てやはんだ付けの手順は [Wiki](https://github.com/KikuchiMakoto/modbus_simple_pcb/wiki) にまとめてあります。基本的にはWikiの内容だけで完結します。

## ガーバーデータ・図面データ

発注に必要なガーバーデータや図面データは [Releaseページ](https://github.com/KikuchiMakoto/modbus_simple_pcb/releases) に置いてあります。

## NDIS/BNC端子・ケース加工

基板本体以外のNDIS/BNC端子の取り付けやケース加工は、出入りの業者に依頼すれば対応してもらえます。

## ライセンス

本リポジトリの回路図・PCB レイアウト・フットプリント・シンボル等の**ハードウェア設計ファイル**は
**CERN Open Hardware Licence Version 2 — Strongly Reciprocal (CERN-OHL-S 2.0)** の下で公開しています。
詳細はリポジトリ同梱の [`LICENSE-CERN-OHL-S-2.0.txt`](./LICENSE-CERN-OHL-S-2.0.txt) を参照してください。

- SPDX: `CERN-OHL-S-2.0`
- 派生物は同じライセンスでの配布が必要です（strong copyleft）。
- KiCad のプロジェクトファイル、Gerber、回路図シンボル／フットプリントが対象です。

ファームウェア ([modbus_simple_firmware](https://github.com/KikuchiMakoto/modbus_simple_firmware)) は MIT、
ドキュメント ([modbus_simple_system](https://github.com/KikuchiMakoto/modbus_simple_system)) も MIT です。
リポジトリごとにライセンスが異なるため、混在させる場合はそれぞれの LICENSE を確認してください。
