# muse-gadget-sdk-jiskan

Muse Gadget SDK 用の日本語専用フォントです。  
JIS X 0213 の第1面・第2面をもとに 11,208 字を収録  
既存は JIS X 0213 第2面が入ってないため、豆腐になる。
- こちらは JIS X 0213 で切った日本語専用。その代わり日本語以外と半角カナは入っていない。行の高さは 17 → 16。
標準の `muse_font_cjk_16.c` と同じ場所に、同名に改名して置き、そのままビルドする。戻すときは標準ファイルに戻すだけ。

## 出典

- 字形：Jiskan16 の BDF 原典（パブリックドメイン）— Unifoundry の Japanese Font Encodings ページ掲載の `jiskan16-2004-1.bdf.gz`（第1面）と `jiskan16-2000-2.bdf.gz`（第2面）。取得時に SHA256 照合済み。
- 変換：`jiskan16_to_lvgl.py`
- 数値は生成ファイル（2026-11-05）の実測。
