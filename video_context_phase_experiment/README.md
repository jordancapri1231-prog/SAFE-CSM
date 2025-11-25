CPF External Observation Log — Contextual Phase Stability Test (SAFE-CSM Public Layer)

This repository contains external observation logs and analytical summaries
produced using the CPF (Contextual Premise Framework) and the SAFE-CSM public stability layer.
All data is collected purely through external interaction with an LLM.
No internal model parameters, training data, or proprietary components are accessed or modified.

The purpose of this repository is to provide transparent examples of:

context drift detection

phase shift observation

fixation / release cycles

long-horizon contextual stability

externally observable response regimes

These materials demonstrate how phase transitions can be evaluated in LLMs
through external context observation only, following SAFE-CSM’s design principles.

Contents
1. Observation Logs（Original / JA）

Unmodified logs of contextual-phase transitions recorded during extended interaction.
These files preserve all symbols, spacing, and rendering artifacts (including □□).
This formatting is intentional and reflects the raw output as observed.

2. Analytical Summaries（EN / JA）

Interpretations of observed phase behavior based on CPF/SAFE-CSM.
These summaries describe:

detected phase patterns

drift characteristics

reversible and irreversible transitions

fixation loops and release states

stability across extended sequences

The summaries provide context without modifying the raw logs.

3. Video Demonstration

A screen-captured run of the same external observation process.
This video illustrates the live sequence of:

state transitions (A–N)

phase reversals

drift accumulation

stabilization patterns

The video is optional but useful for visual understanding.

Methodology

All data was obtained using:

natural-language inputs

external observation only

no model tuning or parameter access

SAFE-CSM compliant drift tracking

CPF-based contextual-phase interpretation

The experiment does not evaluate internal architecture, alignment, or safety tuning.
It is strictly an external stability observation protocol.

File Format Policy

Raw logs are distributed in .txt format to preserve original formatting.

Analytical summaries are provided in .txt for maximum compatibility.

No PDF conversions are used for Japanese text to avoid encoding issues.

No translation is applied to raw logs.

Intended Use

These materials are provided for:

researchers studying context drift

engineers evaluating long-sequence behavior

organizations considering external stability layers

educational and transparency purposes

This repository represents the SAFE-public layer only.
It does not include any NDA-restricted structures or implementation logic.


CPF 外部観測ログ — 文脈相位安定テスト（SAFE-CSM 公開レイヤ）

このリポジトリは、
CPF（Contextual Premise Framework） と
SAFE-CSM 公開安定レイヤを用いて取得した
「文脈相位（phase）遷移の外部観測ログ」、
およびその解析結果をまとめたものです。

ここで公開しているデータはすべて、

LLM の内部情報やパラメータには一切アクセスせず

外部からの自然言語入力だけで

文脈のドリフト（Δ）、相位変化、固着・解放などを観測したもの

であり、
SAFE-CSM が定める “外部観測のみ” の原則に従っています。

■ 内容構成
1. 観測ログ（生データ / 日本語）

LLM との連続対話から得られた、文脈相位の遷移ログです。
スペース・不可視文字・□□（文字化け）なども
すべて“生データそのまま” を保持しています。

これらの文字は、モデルが出力した状態を忠実に残すため、
加工せずに公開しています。

2. 解析結果（日本語 / 英語）

CPF・SAFE-CSM の観測原則に基づき、ログに現れた：

文脈状態（A〜N）の変化

反転指示による相位遷移

固着ループと解放フェーズ

文脈ドリフトの方向性

長期的な安定／発散傾向

などを整理した解析文書です。

生ログの意味づけを行うための資料であり、
ログ本体は加工していません。

3. 動画デモ

CPFによる外部観測テストを
画面キャプチャとして収録した動画です。

文脈状態の推移

位相反転

固着／緩和パターン

長期的な応答の周期性

などを可視的に確認できます。

動画は補助資料のため、
なくても解析は可能 です。

■ 方法論（Methodology）

このログはすべて、

自然言語のみでの対話

モデル内部へ干渉なし

外部の微小揺らぎ（expression shift）による観測

SAFE-CSM の drift tracking を利用

CPF の文脈相位モデルに基づく解釈

で得られています。

これは アライメント実験でもチューニングでもなく、
純粋な 外部安定観測プロトコル による記録です。

■ ファイル形式について

生ログ・解析結果ともに .txt 形式 を採用

日本語 PDF は文字化けが発生するため使用しない

ログは翻訳せず、原文のまま公開

解析結果は日本語・英語の両方を用意

これにより、
再現性・可搬性・長期保存性が最適化 されています。

■ 利用目的

このリポジトリは以下の用途を想定しています：

文脈ドリフトの研究

長期応答の安定性評価

外部安定レイヤの参考資料

CPF/SAFE-CSM の理解支援

研究・教育・解析用途

本リポジトリに含まれるのは
SAFE-CSM の “公開レイヤ” のみ であり、
NDA対象の実装・内部構造は含みません。
