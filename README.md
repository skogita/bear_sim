# Tohoku Wildlife ABM (bear & deer) — companion source for the book

Design documents and code for the simulator built in ***Toward a Million Lines V — Building a Behavior Simulator for Bears and Deer*** (Japanese title 『LLM で 100 万行のソフトウェア開発 V — 熊と鹿の行動シミュレータをつくる』).

An individual-based simulation of Asiatic black bears and sika deer in Tohoku, Japan, on a grid of vegetation, terrain, climate and human-activity layers (standard regional mesh, about 1 km; 600 x 224 cells). The computation is canonical in Python; the screen (Windows and Android) only draws. **It is not a forecasting tool**: the absolute head counts are not accurate.

## Download

**Ready-to-run apps are on the [Releases](../../releases) page**, not in this repository. The release has five separate ZIPs:

| File | Contents |
|:---|:---|
| `bear_sim_exe.zip` | Windows app, Japanese screens (version 0.15.3) |
| `bear_sim_apk.zip` | Android APK, Japanese screens (version 0.15.3) |
| `bear_sim_exe_en.zip` | Windows app, English screens (version 0.15.3) |
| `bear_sim_apk_en.zip` | Android APK, English screens (version 0.15.3) |
| `bear_sim.zip` | Design documents and source code: `docs_src/` (Japanese, L1-L4, the source) and `docs_en/` (the complete set for the English edition: L1-L3 translated into English, L4 the Japanese originals as is) in separate folders, `src/`, `desktop/`, `app/`, `shared/`, an empty ledger |

The Windows build needs Python 3.11 with numpy on your PC. The Android build is debug-signed; the author ran it on an Android device and confirmed it (version 0.15.3). The apps are **not code-signed**, so Windows and Android may warn you.

You are free to change the design documents and the code and compare the results.

---

## License

- **The author holds the copyright.**
- **The code is under the GNU General Public License v3.0 (GPL-3.0).** The full text is [`LICENSE`](LICENSE). **If you modify it and distribute it, you must publish the source under the same GPL-3.0.**
- **The design documents and the text are under the Creative Commons Attribution-ShareAlike 4.0 International license (CC BY-SA 4.0).** This covers `docs_src/`, `docs_en/`, the READMEs and the other written text of this repository, and the text of the matching book. See [`LICENSE-DOCS.md`](LICENSE-DOCS.md).
- **If you use them, say so.** State where it came from (the title of the book and the name of this repository) and keep the copyright notice. If you changed it, say that you changed it.
- **In this project the design documents are the source of the code.** When you publish something made from this code, **publish the design documents together with the code.**
- Third-party components used by the apps remain under their own original licenses.
- Provided "as is", without warranty — as the GPL-3.0 text says.

## 著作権とライセンス

- **著作権は、著者にあります。**
- **コードは、GNU General Public License v3.0（GPL-3.0）です。**全文は [`LICENSE`](LICENSE) です。**改変して配布するときは、同じ GPL-3.0 で、ソースを公開する義務があります。**
- **設計書と文章は、Creative Commons 表示-継承 4.0 国際（CC BY-SA 4.0）です。**内容は [`LICENSE-DOCS.md`](LICENSE-DOCS.md) です。
- **使ったときは、使ったことを書いてください。**直したときは、直したことも書いてください。
- **このプロジェクトでは、設計書がコードの源です。**コードを使って作ったものを公開するときは、**設計書も、コードと一緒に公開してください。**
- 現状のまま（as is）提供します。保証はありません（GPL-3.0 の全文のとおりです）。
