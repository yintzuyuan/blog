# Chirpy 入門

[![Gem 版本](https://img.shields.io/gem/v/jekyll-theme-chirpy)][gem]&nbsp;
[![GitHub 授權](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]

透過 [RubyGems.org][gem] 安裝 [**Chirpy**][chirpy] 主題時，Jekyll 只能讀取主題 gem 中的 `_data`、`_layouts`、`_includes`、`_sass` 和 `assets` 資料夾內的檔案，以及 `_config.yml` 檔案中的一小部分設定。若您曾安裝此主題 gem，可使用指令 `bundle info --path jekyll-theme-chirpy` 找到這些檔案。

Jekyll 團隊表示這是為了讓使用者擁有更多自主權，但這也導致使用者在使用功能豐富的主題時，無法享受開箱即用的體驗。

要完整使用 **Chirpy** 的所有功能，您需要從主題的 gem 複製其他關鍵檔案到您的 Jekyll 網站。以下是需要的檔案列表：

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

為了節省您的時間，同時避免複製過程中遺失檔案，我們已將 **Chirpy** 主題最新版本的這些檔案/設定和 [CD][CD] 工作流程整理至此，讓您能夠快速開始寫作。

## 使用方式

請參閱[主題文件](https://github.com/cotes2020/jekyll-theme-chirpy/wiki)。

## 貢獻

此儲存庫會自動更新主題儲存庫的新版本。如果您遇到任何問題或想協助改進，請至[主題儲存庫][chirpy]提供意見回饋。

## 授權

本作品採用 [MIT][mit] 授權條款發布。

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE