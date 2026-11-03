# KoiChem アプリ紹介（koichem.github.io）

KoiChem が公開している化学学習・授業向け Web アプリの紹介ページです。
各アプリのスクリーンショット（2〜4枚）・簡単な紹介文・リンク（アプリ／GitHub）を並べています。

公開URL: https://koichem.github.io/

## 掲載アプリ

| アプリ | アプリURL | リポジトリ |
|---|---|---|
| アルカンパズル | https://koichem.github.io/AlkanePuzzle/ | KoiChem/AlkanePuzzle |
| IonicFormula | https://koichem.github.io/IonicFormula/ | KoiChem/IonicFormula |
| 限界半径比いじくるくん | https://koichem.github.io/GenkaiHankeiHi/ | KoiChem/GenkaiHankeiHi |
| ステレオ分子くん | https://koichem.github.io/StereoMolecule/ | KoiChem/StereoMolecule |
| ベンゼン共鳴構造くん | https://koichem.github.io/resonance_kun/ | KoiChem/resonance_kun |
| 有機化合物ビンゴ | https://koichem.github.io/OrgoBingo/ | KoiChem/OrgoBingo |
| 元素記号ビンゴ | https://koichem.github.io/bingo_kun/ | KoiChem/bingo_kun |
| SekiGae（席替え） | https://koichem.github.io/SekiGae/ | KoiChem/SekiGae |
| 化学式コピペくん | https://koichem.github.io/copype_kun/ | KoiChem/copype_kun |
| PDF Crop & Export | https://koichem.github.io/PdfCrop/ | KoiChem/PdfCrop |

全アプリの一覧は既存ポータル https://koichem.github.io/Apps/ にあります。

## 構成

- `index.html` — 単一ファイル（アプリ情報はページ内の `APPS` データで管理）
- `assets/*.jpg` — 各アプリのスクリーンショット

## アプリの追加方法

1. `assets/` にスクリーンショット（横長、目安 1200×750）を置く
2. `index.html` の `APPS` にエントリを追加し、`GROUPS` の該当グループへキーを足す
