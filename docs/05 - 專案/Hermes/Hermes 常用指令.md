---
tags: [hermes, 設定]
created: 2026-06-04
---

# 🤖 Hermes 常用指令

## 🚀 啟動與重啟

```bash
hermes gateway run --replace    # 取代現有 gateway 重啟
hermes chat                     # CLI 模式
```

## ⚙️ Model 切換

```bash
# V4 Flash（複雜任務用）
hermes config set reasoning.enabled false
hermes config set model deepseek-v4-flash

# DeepSeek Chat（省錢/日常用）
hermes config set model deepseek-chat
```

## 📅 Cron Job 管理

```bash
hermes cron list    # 列出所有排程
hermes cron run <id>  # 手動執行
```

## 🔧 其他

- Telegram bot: @pjacheng_bot
- 技能目錄：`hermes skills`
- Gateway 日誌：`hermes gateway logs`
