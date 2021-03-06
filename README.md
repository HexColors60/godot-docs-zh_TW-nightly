# 關於 About This Repo

(English follow by Chinese)

由於 Godot 官方的文件網站不會即時從 Weblate 上更新翻譯（而且久久才更新一次），
而繁體中文的翻譯現在正在火熱進行中，所以這裡提供一個每天會自動 Build 中文文件的功能。

前往 https://binotaliu.github.io/godot-docs-zh_TW-nightly/ 看目前的版本。
Go ahead to https://binotaliu.github.io/godot-docs-zh_TW-nightly/ to see the latest build.


## 這個是怎麼運作的？ How Does This Work?

這個 Repo 使用 GitHub Action 來在每天 UTC 時間 18:00 執行（相當於台北或香港時間的 2:00），
執行了 Action 後會自動將 Sphinx 產生的靜態頁面放到本 Repo 的 gh-pages 上，這樣就部署了 GitHub Pages。

This Repo scheduled a GitHub Action workflow to run every day at 18:00 UTC (equals to 2:00 of Taipei or Hong Kong local time.)
By runnign the Action, the static pages generated by Sphinx will be pushed to the gh-pages branch of this repo. Which means deployed to GitHub Pages.

## 授權 License

All the translation content of this repository (`msgid`, `msgstr`) is
licensed under the Creative Commons Attribution 3.0 Unported license
([CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)) and is to be
attributed to "Juan Linietsky, Ariel Manzur and the Godot community".

See [LICENSE.txt](/LICENSE.txt) for details.

The shell scripts are in the public domain.
