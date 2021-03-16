# ニコ動クルーズ

<!-- # Short Description -->

ニコ生クルーズの動画版です。<br />
生放送を巡回するのではなく、動画を巡回します。

<!-- # Badges -->

![GitHub Pipenv locked Python version](https://img.shields.io/github/pipenv/locked/python-version/NUCO-studio/Nico-video-cruise?style=for-the-badge)

![Travis (.com)](https://img.shields.io/travis/com/NUCO-studio/Nico-video-cruise)
![Requires.io](https://img.shields.io/requires/github/NUCO-studio/Nico-video-cruise)
![GitHub all releases](https://img.shields.io/github/downloads/NUCO-studio/Nico-video-cruise/total)
![GitHub](https://img.shields.io/github/license/NUCO-studio/Nico-video-cruise)

# Tags

`niconico` `ニコ生` `python3`

# Demo

![Demo](resources/file-0.png)

# Advantages

- 自動で引用する動画を切り替えます
- タグ指定でランダムクルーズさせる他、キューを与えて指定順でクルーズさせることもできます
- ランダムクルーズ時はNG指定された動画やNGタグを含む動画をクルーズしません
- 単体動作だけでなく、モジュールとして他のプログラムに組み込めます
- Python環境さえあればOSに依存しません

# Installation

（Win機は`python -m`を`py -m`に読み替えてください）

0. Pip導入。方法は [こちら（外部サイト）](https://pip.pypa.io/en/stable/installing/)。

1. `python -m pip install nvcruise`

2. `python -m nvcruise config`

3. 画面の指示に従い初期設定

# Minimal Example

### 単体実行

`python3 -m nvcruise`

### モジュールとして使用

```python 
import nvcruise

# "lv123456"は放送中・放送前の番組ID
cruise = nvcruise.ship("lv123456")
cruise.start()
```

# Contributors

- [NUCO-studio](https://github.com/NUCO-studio)

# Users

- [NUCOSen](https://nucosen.live)

<!-- CREATED_BY_LEADYOU_README_GENERATOR -->