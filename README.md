# Minecraft CIT Template

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.61--1.21-blue)

[![Use Template](https://img.shields.io/badge/-Use%20Template-blue?logo=github)](https://github.com/new?template_name=YOUR_TEMPLATE_NAME)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🙏 謝辞（Acknowledgment）

本プロジェクトの最適化処理は，オープンソースツール **[PackSquash-action](https://github.com/ComunidadAylas/PackSquash-action)** によって実現されています．  
開発チームの皆様に心より感謝申し上げます．

---

## 🚀 クイックスタート（Quick Start）

1. **[Use Template]** ボタンをクリックし，新規リポジトリを作成．
2. 作成したリポジトリをローカル環境にクローン．
   ```sh
   git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   ```
3. `assets/minecraft/optifine/cit/` にカスタムテクスチャを追加．
4. GitHub Actions によりリソースパックが自動でビルドされます．

---

## 📦 サンプル（Samples）

このテンプレートには以下のサンプルが含まれています：

![Image](https://github.com/user-attachments/assets/e6b086e5-b1b7-4594-8c69-d97b6e0667a4)

- **サンプル A**：アイテムにカスタムテクスチャを適用．
- **サンプル B**：ブロックにカスタムテクスチャを適用．
- **サンプル C**：アイテムにアニメーションテクスチャを適用．
- **サンプル D**：ブロックにカスタムモデルを適用．

## 🛠️ カスタマイズ例（Customization Example）

以下のプロパティを設定することで，特定のアイテムにカスタムテクスチャを適用できます．

```properties
type=item
items=minecraft:stick
texture=sampleA
nbt.display.Name=sampleA
```

---

## 📜 Pack Format 対応表（Pack Format Compatibility）

| pack_format | Minecraft Version |
| ----------- | ----------------- |
| 1           | 1.61-1.89         |
| 2           | 1.9-1.10.2        |
| 3           | 1.11-1.12.2       |
| 4           | 1.13-1.14.4       |
| 5           | 1.15-1.16.1       |
| 6           | 1.16.2-1.16.5     |
| 7           | 1.17-1.17.1       |
| 8           | 1.18-1.18.2       |
| 9           | 1.19-1.19.2       |
| 12          | 1.19.3            |
| 13          | 1.19.4            |
| 15          | 1.20-1.20.1       |
| 18          | 1.20.2            |
| 22          | 1.20.3-1.20.4     |
| 32          | 1.20.5-           |
| 34          | 1.21-             |

### `pack.mcmeta` の例:

```json
{
  "pack": {
    "pack_format": 8, // ver1.18.2
    "description": "My Pack"
  }
}
```

---

## 🔗 参考リンク（Resources）

より詳しい情報は，以下のリンクをご参照ください：

- [OptiFine ドキュメント](https://optifine.readthedocs.io/index.html)
- [PackSquash オプションファイル](https://github.com/ComunidadAylas/PackSquash/wiki/Options-files)
