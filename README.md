# gma-plugin-template

## 專案說明

```makefile
.
├── custom-plugins  # 燈光設計師社群自己開發的 plugin
└── plugins         # grandMA2 官方 plugin
    ├── requirements
    │   └── socket
    └── systemtests
        └── other
```

[grandMA2 官方文件](https://help2.malighting.com/Page/grandMA2/plugins_edit/pt/3.3)其實並沒有公開有哪些可使用的 api，或是教學如果撰寫可兼容的 plugin，僅有說可以使用 Lua 編寫 plugin。

這是網路上少有的 [plugin 教學影片](https://www.youtube.com/watch?v=YSSFk0eU0gg)，內容主要是在基礎的 Lua 語法。

大部分的 plugin 都是由燈光社群自行撰寫並分享，下列則是社群自行整理的 plugin 相關資源：

- [GrandMA2 LUA Reference](https://static.impactsf.com/GrandMA2/index.html)
- [grandMA2 Wiki](https://grandma2.fandom.com/wiki/Object_space_crawler_script)
- [CDS - MA2 lua](https://caodashi.com/ma-lua)
- [grandMA2 Plugins & Lua Scripts 官方論壇](https://forum.malighting.com/forum/board/41-grandma2-plugins-lua-scripts/)

## grandMA2 軟體說明

目前台灣主流的燈光設計編程軟體為 grandMA2，該軟體只能於 **Windows** 作業系統上運行，此為[下載連結](https://www.malighting.com/downloads/products/grandma2/)，目前最新版本為 3.9.60.91。

![grandMA2 下載頁面](/images/Screenshot%202025-07-01%20at%2010.20.30 AM.png)
_grandMA2 下載頁面_

在 grandMA2 中，有自己的 [syntax 跟 keyword](https://help2.malighting.com/Page/grandMA2/command_syntax_and_keywords/en/3.9)，而我們的目標是希望可以使用 AI 工具產出 plugin，而這些 plugin 則可以去操作 grandMA2 原生的語言，進而減少燈光師重複作業與背誦語法的時間。