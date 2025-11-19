SAFE-CSM — Hub Repository

Central directory for all SAFE-CSM public editions

This repository serves as the central hub linking all public SAFE-CSM editions:

LLM Edition

Industry Edition

Core Edition（初期評価モジュール）

Each edition provides SAFE-layer external observation tools for contextual stability analysis,
focusing on phase-difference drift (Δφ), contextual fixations, and over-divergence behavior.

SAFE-CSM frameworks never access model internals, never train or tune models,
and operate entirely through externally observable output signals only.

🔷 English
Overview

SAFE-CSM (SAFE Context Stabilization Module) is a set of non-adaptive, external observation frameworks
designed to evaluate stability, drift, oversynchronization, and divergence in AI and contextual-output systems.

This Hub repository provides:

Links to all SAFE-CSM public editions

OSF DOIs for academic reproduction

GitHub repositories containing source code and figures

Notes on SAFE-layer usage and NDA-protected components

This Hub does not contain code.
Each edition has its own repository.

📁 Included SAFE-CSM Editions
1. SAFE-CSM — LLM Edition

SAFE-layer external observation for Large Language Models.
Contains Δφ drift measurement, stability band demonstration, and output-only evaluation.

GitHub:
https://github.com/jordancapri1231-prog/SAFE-CSM-LLM-Edition

OSF DOI:
10.17605/OSF.IO/VAURE

2. SAFE-CSM — Industry Edition

SAFE-layer external observer for industrial / control-like contextual drift patterns.
Focuses on drift stability within defined SAFE bands, using Δφ-based evaluation.

GitHub:
https://github.com/jordancapri1231-prog/SAFE-CSM-Industry-Edition

OSF DOI:
10.17605/OSF.IO/FJUWS

3. SAFE-CSM — Core Edition (Early Evaluation Module)

The foundational SAFE-layer minimal module.
Simplest, model-agnostic Δφ drift demonstration using only externally observable signals.
Used as the initial evaluation and teaching version.

GitHub:
https://github.com/jordancapri1231-prog/SAFE-CSM-Core

OSF DOI:
10.17605/OSF.IO/4RMZ7

🧪 Academic Use & Reproduction

For academic citation, please cite each edition’s DOI individually.
All repositories are SAFE-layer only and contain no adaptive control,
no model internals, no psychological models, and no reinforcement loops.

SAFE-CSM advanced versions（LLM-integrated / cognitive multi-factor versions）
are managed separately under NDA-protected, non-public implementations.

🤝 Research & Collaboration

Researchers or organizations working on:

AI safety

LLM contextual drift mitigation

Stability evaluation

Human-AI interaction reliability

Cognitive-structure-based analysis

are welcome to contact for SAFE-layer information exchange or joint evaluation.

📨 Contact:
jordan.capri.1231@gmail.com


🇯🇵 日本語（Japanese）
概要

SAFE-CSM は、AI・LLM・工業システムなどの文脈出力に対して
外部から Δφ（位相差）ドリフトを観測し、過同期・過発散を評価する SAFE 層フレームワークです。

モデル内部にはアクセスせず、
学習・最適化・強化も行わない
完全外部観測の非適応 SAFE モジュールです。

この Hub リポジトリは、すべての SAFE-CSM 公開版への
リンク・DOI・説明をまとめた “中枢ディレクトリ” です。

📁 公開 SAFE-CSM エディション
■ SAFE-CSM（LLM版）

LLM の文脈ドリフト・固着・オーバーシンクを SAFE 帯域で評価する外部観測デモ。

GitHub:
https://github.com/jordancapri1231-prog/SAFE-CSM-LLM-Edition

OSF DOI:
10.17605/OSF.IO/VAURE

■ SAFE-CSM（産業版）

産業的な文脈変動や Δφ ドリフトを
SAFE 帯で安定化させるための外部観測デモ。

GitHub:
https://github.com/jordancapri1231-prog/SAFE-CSM-Industry-Edition

OSF DOI:
10.17605/OSF.IO/FJUWS

■ SAFE-CSM（Core版 / 初期評価モジュール）

最小構成の SAFE 層フレームワーク。
Δφ ドリフトの基礎観測を行う “教育用・基礎研究用” 版。

GitHub:
https://github.com/jordancapri1231-prog/SAFE-CSM-Core

OSF DOI:
10.17605/OSF.IO/4RMZ7

🔒 NDA・非公開 SAFE-CSM について

本 Hub および公開版は、
SAFE層（外部観測のみ）に限定した SAFE-CSM を公開しています。

LLM統合 SAFE-CSM、多因子認知版 SAFE-CSM などの
高度実装は NDA 前提の非公開コード として管理されています。

📬 問い合わせ（共通）

研究連携・技術相談・SAFE層情報交換など
SAFE-CSM 関係の連絡はこちらへ。

jordan.capri.1231@gmail.com
