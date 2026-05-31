# AI Agent × Harness — 動畫解說重製

把一支中文 YouTube 解說影片（[AI Agent工作原理是什么，Harness又是什么](https://www.youtube.com/watch?v=B91bZL8wcAI)，頻道：轩辕的编程宇宙）用全新風格重製，並做成可逐幀檢視的 Canvas 預覽器。

## 🔗 線上預覽

**[👉 點此開啟逐幀動畫預覽器](https://jerrypeace.github.io/agent-harness-preview/)**

- 21 個場景，可逐頁切換
- 播放動畫、時間軸逐幀拖曳
- 統一正黑體（Noto Sans TC）+ Duotone 雙色設計

## 📁 內容

| 路徑 | 說明 |
|------|------|
| `index.html` | Canvas 逐幀動畫預覽器（單檔自含）|
| `transcript/transcript-raw.txt` | 原影片逐字稿（whisper.cpp 本機語音轉錄）|
| `transcript/summary.md` | 結構化內容摘要（Agent 四要素 + Harness）|
| `images/source-frames/` | 原影片 22 張節點截圖 + 總覽 montage |
| `images/remotion-stills/` | Remotion 重製版的渲染截圖 |

## 🎨 設計

- **風格**：Editorial Block / Duotone（參考 ui-ux-pro-max 設計引擎建議）
- **配色**：紙色 `#F4F1E8` + 墨黑 `#1B1B1F` + 珊瑚紅 `#EE4D2E`
- **字型**：統一 Noto Sans TC（正黑體），僅以字重變化
- **技術**：HTML5 Canvas 逐幀動畫；另有 Remotion (React) 影片版

## 📺 內容大綱

1. **Agent 四大核心**：工具調用 → ReAct 循環 → 記憶與上下文管理 → 多智能體協作
2. **Harness（馬具）**：包在 AI 外面的防護網 — 輸入過濾、格式清洗、參數校驗、輸出檢測、錯誤重試
3. **結論**：Agent 解決「怎麼幹活」，Harness 解決「怎麼把活幹得靠譜」
