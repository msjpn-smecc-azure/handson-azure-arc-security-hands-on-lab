# Azure Arc と Microsoft Defender for Servers ハンズオンラボ

このハンズオンラボでは、オンプレミス環境にあるサーバーを Azure Arc を使用してオンボーディングし、Microsoft Defender for Servers を適用してセキュリティ監視を設定します。

## ラボの目的

このラボを完了することで、以下のスキルを習得できます：

1. Azure Arc を使用したオンプレミスサーバーのオンボーディング
2. Microsoft Defender for Servers の有効化と設定

## 実装パターン

このハンズオンラボでは、以下の 2 つの実装パターンをサポートしています：

1. **Azure VM パターン**：Azure 仮想マシンを使用してオンプレミス環境をシミュレーション
2. **オンプレミス VM パターン**：実際のオンプレミス環境にある Windows Server 仮想マシンを使用

どちらのパターンも同じ手順で進めることができ、モジュール 1 でお好みのパターンを選択していただけます。

## ラボの概要

このラボは以下のモジュールで構成されています：

1. **[モジュール 1](modules/module01.md)**: 環境のセットアップと前提条件の確認
1. **[モジュール 2](modules/module02.md)**: Azure Arc でのサーバーオンボーディング
1. **[モジュール 3](modules/module03.md)**: Microsoft Defender for Servers の有効化と構成
1. **[モジュール 4](modules/module04.md)**: Azure Update Manager を使用したパッチ管理
1. **[モジュール 5](modules/module05.md)**: Azure Arc 対応サーバーや Azure VM の情報を Power BI で一元可視化
1. **[モジュール x](modules/module99.md)**: クリーンアップ

## 対象者
- インフラストラクチャ管理者
- セキュリティ管理者
- クラウドアーキテクト
- IT 運用担当者

## 前提条件

- Azure サブスクリプション
- 基本的な Azure ポータルの操作知識
- 基本的な Windows サーバー管理の知識
- PowerShell の基本的な知識

## 課金に関する注意事項

このハンズオンラボでは、以下の Azure リソースを使用します。これらのリソースには費用が発生する可能性があります：

1. **仮想マシン（VM）**
2. **Azure Arc**
3. **Microsoft Defender for Servers**

> **注意**: 最新の料金情報については、[Azure 料金計算ツール](https://azure.microsoft.com/ja-jp/pricing/calculator/)を参照してください。
