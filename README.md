<div align="center">

# DRIFT

### 完全ローカル完結型 AI チャットアプリ (Android)

[![Platform: Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android&logoColor=white)](#)
[![Inference: llama.cpp](https://img.shields.io/badge/Inference-llama.cpp-000000?style=flat)](https://github.com/ggml-org/llama.cpp)
[![Status: Concept](https://img.shields.io/badge/Status-Concept-orange?style=flat)](./CONCEPT.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat)](#ライセンス)

**端末からインターネットに出ずに、キャラクターと会話するためのクライアント。**

---

</div>

## 概要

クラウド LLM に投げたくない種類の会話 — ロールプレイ、個人的な相談、機微な話題 — を、端末の外へ一歩も出さずに行うためのチャットアプリ。

推論は端末内で完結 (llama.cpp / NDK / arm64)。会話履歴もローカルストレージのみ。ネットワークは使わない。

## 特徴

| 項目 | 内容 |
|---|---|
| プライバシー | 会話が運営・サーバ・クラウドに送られない |
| 擬似無限コンテキスト | 階層化メモリで小型モデルでも長期会話が破綻しない |
| キャラ一貫性 | 長期間話し続けても相手が「忘れない」設計 |
| 記憶の掌握 | ユーザーが記憶を閲覧・編集・削除・ピン留めできる |
| モデル差し替え | GGUF 形式で好きな量子化モデルを持ち込める |

## 状態

コンセプトフェーズ。全体設計は [CONCEPT.md](./CONCEPT.md) を参照。

## ライセンス

MIT © 2026 cUDGk
