# AI 工具實作工作坊 · 學員資源站

單頁課程輔助站（講師 何佳勳 / 小圭｜圭話行銷）。

提供學員：
- 🗳️ 今日投票（Slido）連結
- 🧰 核心工具總覽（ChatGPT / Gemini / AI Studio / Claude / MCP）外連
- 🎯 提示詞七元素框架（互動展開）
- 📋 可一鍵複製的提示詞範本（社群文案、時事 SOP、標題、風格變體、PRD）
- ⚖️ 平台比較、PRD/SSD 開發方法、部署 × API × 資安
- 🔌 MCP 與必裝工具清單
- 🚀 現場 DEMO 工具「AI 工作流拆解專家」自動分流（AI Studio 版 / ai101 版 50/50）
- 🎮 **遊戲化學習**：進場報名寫名字 → 互動累積學習點數（複製提示詞 +5、展開七元素 +2、投票 +15、啟動 DEMO +10、看完 +6…）→ 達 60 點自動解鎖 → 一鍵下載專屬**結業證書 PNG**

## 每場可調設定（index.html 內 `CONFIG`）

```js
const CONFIG = {
  ENABLE_GROUPS: false,   // 這場需要分組就改 true，報名時會多一個分組下拉
  GROUPS: ['A 組','B 組', ...],
  CERT_THRESHOLD: 60,     // 領證書所需點數
  COURSE_NAME: 'AI 工具實作工作坊',
  LECTURER: '何佳勳（小圭）'
};
```

> 點數與名字存在學員瀏覽器 localStorage（純前端，無後端、無個資外流風險）。

## 部署

純靜態單頁，GitHub Pages 直接託管 `index.html`。

線上網址：https://atm301.github.io/ai-tool-workshop/
