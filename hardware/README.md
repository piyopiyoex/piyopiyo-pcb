# hardware

`hardware/` には、Piyopiyo PCB のハードウェア設計データをまとめています。

主な内容は次のとおりです。

```text
hardware/
├── vX.Y/                         # バージョンごとの設計データ一式
│   ├── kicad/                    # KiCad プロジェクト一式（.kicad_pro/.kicad_sch/.kicad_pcb 等）
│   │   └── piyopiyo-pcb-vX.Y/    # プロジェクトフォルダ（フットプリント/ライブラリ含む）
│   ├── fab/
│   │   └── jlcpcb/               # JLCPCB 向け製造データ
│   │       ├── bom.csv           # 部品表（LCSC Part # を含む）
│   │       ├── cpl.csv           # 部品実装位置（Pick & Place）
│   │       └── gerber.zip        # 基板製造用 Gerber 一式
│   └── docs/
│       └── piyopiyo-pcb.pdf      # 回路図・基板レイアウトの PDF 出力
├── reference/                    # モジュール寸法などの参考資料
└── CHANGELOG.md                  # バージョン間の変更履歴
```

## ライセンスと帰属

このディレクトリのハードウェア設計データは kurokouji により作成されました。

ライセンスの詳細は [`LICENSE.md`](../LICENSE.md) を参照してください。
