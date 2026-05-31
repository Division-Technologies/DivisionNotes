# DivisionNotes
Research and documentation repository for [DivisionEngine](https://github.com/Division-Technologies/DivisionEngine).

Every feature implementation in DivisionEngine must be accompanied by documentation summarizing the research and findings behind it.
This repository is where that documentation lives.


## Structure
Documentation is organized by engine layer:

| Directory | Layer | Description |
|---|---|---|
| `Core/` | DivisionEngine.Core（C# → C++） | Research on core engine internals and architecture |
| `Native/` | DivisionEngine.Native（C++） | Research on graphics APIs, OS-level APIs, and native interop |
| `Editor/` | DivisionEngine.Editor（C#） | Research on GUI frameworks, scripting systems, and build pipelines |

## Guidelines
- Document what you researched and learned, not just the final implementation
- Include references to external resources (articles, specifications, source code) used during research
- Write documentation before or during implementation, not after


---


## 日本語
[DivisionEngine](https://github.com/Division-Technologies/DivisionEngine) の調査・ドキュメントリポジトリです。

DivisionEngine では、機能を実装する際に必ず調査結果をドキュメントにまとめる必要があります。
このリポジトリはそのドキュメントを管理する場所です。


## 構成
ドキュメントはエンジンのレイヤーごとに整理されています:

| ディレクトリ | レイヤー | 内容 |
|---|---|---|
| `Core/` | DivisionEngine.Core（C# → C++） | エンジン内部構造・アーキテクチャに関する調査 |
| `Native/` | DivisionEngine.Native（C++） | グラフィックAPI、OS API、ネイティブ連携に関する調査 |
| `Editor/` | DivisionEngine.Editor（C#） | GUIフレームワーク、スクリプティング、ビルドパイプラインに関する調査 |

## ガイドライン
- 最終的な実装だけでなく、調査した内容や学んだことを記述する
- 調査中に参照した外部リソース（記事、仕様書、ソースコード）を記載する
- ドキュメントは実装の前または最中に書くこと。実装後ではない
