<div align="center">

# DRIFT

### 完全ローカル型 AI チャットアプリ (Android)

[![Platform: Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android&logoColor=white)](#)
[![Inference: llama.cpp](https://img.shields.io/badge/Inference-llama.cpp-000000?style=flat)](https://github.com/ggml-org/llama.cpp)
[![Status: Concept](https://img.shields.io/badge/Status-Concept-orange?style=flat)](./CONCEPT.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat)](#ライセンス)

**会話が端末から外に出ない、スマホ向けのキャラチャット。**

---

</div>

## 概要

ChatGPT や Claude みたいなクラウド AI に投げたくない会話 — ロールプレイ、ちょっと人に言いづらい相談、書きかけの創作 — をネットに出さずにやるためのアプリ。

推論は端末の中で直接動かす (llama.cpp + NDK / arm64)。チャット履歴もアプリの中に閉じてる。通信は一切しない。

## できること

| 項目 | 内容 |
|---|---|
| 完全オフライン | 機内モードでも動く |
| 長期会話 | 階層化メモリで、狭いコンテキストでも会話が続く |
| キャラ一貫性 | 長く話しても相手の設定や過去が保たれる |
| 記憶を握れる | 記憶は見える、直せる、消せる |
| モデル自由 | GGUF ならなんでも差し替え可 |

## 状態

まだ構想段階。中身の設計は [CONCEPT.md](./CONCEPT.md) に書いた。

## ライセンス

MIT © 2026 cUDGk
