# TensorFlow Agents

**TensorFlowによる強化学習**

エージェントは、変更および拡張が可能な十分にテストされたモジュール式コンポーネントを提供するため、新しい強化学習アルゴリズムの設計、実装、およびテストが容易になります。また、優れたテストの統合とベンチマークにより、コードのイテレーションが大幅に高速化されます。

はじめるには、[チュートリアル](/tutorials)をご確認ください。

## インストール

TF-Agent は毎晩安定したビルドを公開します。リリースのリストについては、<a href="#Releases">リリース</a>セクションを参照してください。以下のコマンドを実行すると、[pypi.org](https://pypi.org)、または、GitHub クローンから、TF-Agent ステーブル版を毎晩インストールできます。

> :警告: Reverb（リプレイバッファ）の使用は非常に一般的ですが、この場合、TF-Agents は Linux でしか動作しません。

> 注意: Python 3.11 には pygame 2.1.3+ が必要です。

### ステーブル版

以下のコマンドを実行して、最新の安定版リリースをインストールします。このリリースの API ドキュメントは[ tensorflow.org](https://www.tensorflow.org/agents/api_docs/python/tf_agents) からご覧いただけます。

```shell
$ pip install --user tf-agents[reverb]

# Use this tag get the matching examples and colabs.
$ git clone https://github.com/tensorflow/agents.git
$ cd agents
$ git checkout v0.17.0
```

Tensorflow のバージョン、または、pip 依存関係チェックで互換性がないとフラグが付けられている [Reverb](https://github.com/deepmind/reverb) で TF-Agents をインストールする場合、自己責任で以下のパターンを使用してください。

```shell
$ pip install --user tensorflow
$ pip install --user dm-reverb
$ pip install --user tf-agents
```

TensorFlow 1.15 または 2.0 で TF-Agents を使用する場合は、バージョン 0.3.0 をインストールします。

```shell
# Newer versions of tensorflow-probability require newer versions of TensorFlow.
$ pip install tensorflow-probability==0.8.0
$ pip install tf-agents==0.3.0
```

### ナイトリービルド

ナイトリービルドには新しい機能が含まれていますが、バージョン付きのリリースよりも安定性が低い場合があります。ナイトリ―ビルドは、`tf-agents-nightly`としてプッシュされます。TensorFlow のナイトリーバージョン (`tf-nightly`) と TensorFlow Probability (<code>tfp-nightly</code>) のインストールをお勧めします。これらは TF-Agents ナイトリ―がテストされるバージョンです。

ナイトリービルドバージョンをインストールするには、次のコマンドを実行します。

```shell
# `--force-reinstall helps guarantee the right versions.
$ pip install --user --force-reinstall tf-nightly
$ pip install --user --force-reinstall tfp-nightly
$ pip install --user --force-reinstall dm-reverb-nightly

# Installing with the `--upgrade` flag ensures you'll get the latest version.
$ pip install --user --upgrade tf-agents-nightly
```

### GitHub から

リポジトリのクローンを作成したら、`pip install -e .[tests]`を実行して依存関係をインストールできます。TensorFlow は`pip install --user tf-nightly`を実行して個別にインストールする必要があります。

<a id="Contributing"></a>

## コントリビューション

TensorFlow では皆様からのコントリビューションを歓迎しています。コントリビューションについてのガイドは、[`CONTRIBUTING.md`](https://github.com/tensorflow/agents/blob/master/CONTRIBUTING.md)をご覧ください。このプロジェクトは、TensorFlow の[行動規範](https://github.com/tensorflow/agents/blob/master/CODE_OF_CONDUCT.md)に準拠しています。参加することにより、このコードに準拠することに同意したことになります。

<a id="Releases"></a>

## リリース

TF Agents には安定版とナイトリーリリースがあります。多くの場合ナイトリーリリースを使用しても問題はありませんが、上流のライブラリが変動するため、問題が発生する可能性もあります。以下の表は、各 TF Agents リリースに対応する TensorFlow のバージョンを示しています。関連するリリースバージョンは以下のとおりです。

- 0.16.0 は Python 3.11 をサポートした最初のバージョンです。
- 0.15.0 は Python 3.7 に対応する最後のリリースです。
- Numpy &lt; 1.19 を使用している場合は、TF-Agents 0.15.0 およびそれ以前のリリースを使用してください。
- 0.9.0 は Python 3.6 に対応する最後のリリースです。
- 0.3.0 は Python 2.x. に対応する最後のリリースです。

リリース | ブランチ/タグ | TensorFlow バージョン | dm-reverb バージョン
--- | --- | --- | ---
ナイトリー | [マスター](https://github.com/tensorflow/agents) | tf-nightly | dm-reverb-nightly
0.17.0 | [v0.17.0](https://github.com/tensorflow/agents/tree/v0.17.0) | 2.13.0 | 0.12.0
0.16.0 | [v0.16.0](https://github.com/tensorflow/agents/tree/v0.16.0) | 2.12.0 | 0.11.0
0.15.0 | [v0.15.0](https://github.com/tensorflow/agents/tree/v0.15.0) | 2.11.0 | 0.10.0
0.14.0 | [v0.14.0](https://github.com/tensorflow/agents/tree/v0.14.0) | 2.10.0 | 0.9.0
0.13.0 | [v0.13.0](https://github.com/tensorflow/agents/tree/v0.13.0) | 2.9.0 | 0.8.0
0.12.0 | [v0.12.0](https://github.com/tensorflow/agents/tree/v0.12.0) | 2.8.0 | 0.7.0
0.11.0 | [v0.11.0](https://github.com/tensorflow/agents/tree/v0.11.0) | 2.7.0 | 0.6.0
0.10.0 | [v0.10.0](https://github.com/tensorflow/agents/tree/v0.10.0) | 2.6.0 |
0.9.0 | [v0.9.0](https://github.com/tensorflow/agents/tree/v0.9.0) | 2.6.0 |
0.8.0 | [v0.8.0](https://github.com/tensorflow/agents/tree/v0.8.0) | 2.5.0 |
0.7.1 | [v0.7.1](https://github.com/tensorflow/agents/tree/v0.7.1) | 2.4.0 |
0.6.0 | [v0.6.0](https://github.com/tensorflow/agents/tree/v0.6.0) | 2.3.0 |
0.5.0 | [v0.5.0](https://github.com/tensorflow/agents/tree/v0.5.0) | 2.2.0 |
0.4.0 | [v0.4.0](https://github.com/tensorflow/agents/tree/v0.4.0) | 2.1.0 |
0.3.0 | [v0.3.0](https://github.com/tensorflow/agents/tree/v0.3.0) | 1.15.0 および 2.0.0 |

<a id="Principles"></a>

## 原則

このプロジェクトは、[Google の AI 原則](https://github.com/tensorflow/agents/blob/master/PRINCIPLES.md)に準拠しています。 このプロジェクトに参加、使用、またはコントリビューションすることにより、これらの原則を遵守することに同意されたものとします。

<a id="Citation"></a>

## 引用

このコードを使用する場合は、次のように表記してください。

```
@misc{TFAgents,
  title = {{TF-Agents}: A library for Reinforcement Learning in TensorFlow},
  author = {Sergio Guadarrama and Anoop Korattikara and Oscar Ramirez and
     Pablo Castro and Ethan Holly and Sam Fishman and Ke Wang and
     Ekaterina Gonina and Neal Wu and Efi Kokiopoulou and Luciano Sbaiz and
     Jamie Smith and Gábor Bartók and Jesse Berent and Chris Harris and
     Vincent Vanhoucke and Eugene Brevdo},
  howpublished = {\url{https://github.com/tensorflow/agents}},
  url = "https://github.com/tensorflow/agents",
  year = 2018,
  note = "[Online; accessed 25-June-2019]"
}
```
