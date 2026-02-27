# 🚀 Nuxt.js 測試專案

這是一個用於測試與練習 Nuxt.js 框架的專案，旨在探索其核心功能與組件架構。 🏗️

---

## 🛠️ 安裝步驟

你可以點擊查看 [安裝 Nuxt.js 的詳細指南](./docs/Nuxtjs_Init.md)，或是直接在終端機執行以下指令：

```bash
cd Nuxtjs
npm install
```

---

## 🏃 專案執行

使用以下指令啟動開發伺服器：

```bash
npm run dev
```

開發環境啟動後，請查看終端機顯示的網址（預設通常為 http://localhost:3000/）：
🔗 [http://localhost:3000/](http://localhost:3000/)
*(註：若 3000 端口被佔用，Nuxt 會自動切換至其他端口，如 http://localhost:6583/)*

---

## 🏠 首頁結構與組件

專案的首頁文件位於：
`Nuxtjs\pages\index.vue`

```vue
<template>
  <Tutorial/>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
```

### 🧩 組件說明
在範例中看到的 `<Tutorial/>` 是一個組件 (Component)，你可以在以下目錄找到它：
📍 `Nuxtjs\components\Tutorial.vue`

