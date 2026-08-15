> 日本語: 信頼できる英語ソースの機械翻訳。母国語による修正は大歓迎です。 [英語](../../README.md) | [すべての言語](../README.md)

# ツール、モデル、ソース

![監査可能なソース レジストリに保存されるツール、モデル、データセット、バージョン、ロール](../../assets/tool-model-source-index.png)

維持されているデータセンター台帳によって指定されたすべての主要な外部ツールまたはモデルは、ここから公式の公開プロジェクトまたは配布ページにリンクされています。これは直接的な依存関係とモデルのインデックスであり、推移的なソフトウェア部品表ではありません。

ステータス列には、コンポーネントに対して記録された関係が説明されます。廃止または検査されたツールは、現在のランタイム コードとして表示されずにクレジットされたままになります。

実験で名前を付けた外部モデルも同様に、記録システムではありません。その役割は、その実験用に文書化されたペイロードと操作に限定されます。たとえ受信者が提供されたバイトを保持していたとしても、省略されたコーパス、来歴、時間的履歴、およびペイロード構築機構はその依存関係の範囲外に残ります。

| ツールまたはモデル | 公式の公的情報源 | 記録された関係 | 使用者 |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINOモデル | [ソース](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | 上流 | amf_ari、argument_relation_classifier |
| ブリングファイア | [ソース](https://github.com/microsoft/BlingFire) | 上流 | マイクロプランナー、slop_analysis |
| キャディー | [ソース](https://github.com/caddyserver/caddy) | 上流 | TL |
| 特使 | [ソース](https://github.com/envoyproxy/envoy) | 廃止された前任者 (ランタイムではない) | ルーター |
| ファクトCG | [ソース](https://github.com/derenlei/FactCG) | 上流 | セマンティック_オブザーバー |
| ファストAPI | [ソース](https://github.com/fastapi/fastapi) | 上流 | 会話スプリッター、ミッションコントロール、ルーター |
| ファストコアフ | [ソース](https://github.com/shon-otmazgin/fastcoref) | 上流 | 談話_前処理 |
| 高速蒸留ウィスパーラージ v3 | [ソース](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | 上流 | スピーチ |
| より早いささやき声 | [ソース](https://github.com/SYSTRAN/faster-whisper) | 上流 | スピーチ |
| グラフビズ | [ソース](https://gitlab.com/graphviz/graphviz) | 上流 | ミッションコントロール |
| IsaNLP RST | [ソース](https://github.com/tchewik/isanlp_rst) | 上流 | 談話_前処理 |
| 膝をついた | [ソース](https://github.com/arvkevi/kneed) | 上流 | 崩壊パケット |
| リブレチャット | [ソース](https://github.com/danny-avila/LibreChat) | 上流 | チャット |
| ミニチェック | [ソース](https://github.com/Liyan06/MiniCheck) | 上流 | セマンティック_オブザーバー |
| モンゴDB | [ソース](https://github.com/mongodb/mongo) | 上流 | モンゴデータベース |
| ネットワークX | [ソース](https://github.com/networkx/networkx) | 上流 | グラフ投影 |
| NLTK | [ソース](https://github.com/nltk/nltk) | 上流 | スロップ分析 |
| Node.js | [ソース](https://github.com/nodejs/node) | 上流 | チャット |
| Nomic 埋め込みテキスト | [ソース](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | 上流 | ollam_embed |
| オラマ | [ソース](https://github.com/ollama/ollama) | 上流 | オラマ、オラマ_embed |
| OpenVINO | [ソース](https://github.com/openvinotoolkit/openvino) | 上流 | amf_ari |
| ベクター | [ソース](https://github.com/pgvector/pgvector) | 上流 | ポストグレ |
| PostgreSQL | [ソース](https://github.com/postgres/postgres) | 上流 | ポストグレ |
| psutil | [ソース](https://github.com/giampaolo/psutil) | 上流 | ハードウェアテレメトリ |
| サイコプ | [ソース](https://github.com/psycopg/psycopg) | 上流 | ミッションコントロール |
| クウェン3 | [ソース](https://github.com/QwenLM/Qwen3) | 上流 | オラマ、ヴルム |
| スペイシー | [ソース](https://github.com/explosion/spaCy) | 上流 | マイクロプランナー、スロップ分析、サーフェスリアライザー |
| スピーチ | [ソース](https://github.com/speaches-ai/speaches) | 上流 | スピーチ |
| 安定した拡散.cpp | [ソース](https://github.com/leejet/stable-diffusion.cpp) | 上流 | 画像 |
| サブモジュールライブラリ | [ソース](https://github.com/decile-team/submodlib) | 上流 | 崩壊パケット |
| トランスフォーマー | [ソース](https://github.com/huggingface/transformers) | 上流 | セマンティック_オブザーバー |
| ヴィクンジャ | [ソース](https://github.com/go-vikunja/vikunja) | 上流 | ヴィクンジャ |
| vLLM | [ソース](https://github.com/vllm-project/vllm) | 上流 | vllm |
| vLLM セマンティック ルーター | [ソース](https://github.com/vllm-project/semantic-router) | 廃止された前任者 / 検査された系統 (実行時ではない) | ルーター |
| Z-イメージ-ターボ | [ソース](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | 上流 | 画像 |
| Z-Image-Turbo-Windows パッケージング リファレンス | [ソース](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | 検査済みのパッケージングリファレンス (ランタイム UI ではない) | 画像 |

## 分布境界

公開ドキュメントには、リストされたプロジェクトのコードやモデルの重みは含まれていません。将来のソフトウェア配布では、実際に配布されたバイトから正確なバージョン、リビジョン、ハッシュ、推移的な依存関係、モデル条件、およびライセンス テキストを生成する必要があります。プロジェクトのリンクは帰属とトレーサビリティであり、ライセンス意見ではありません。
