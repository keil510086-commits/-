# 大一班会 · 文字冒险游戏

面向大一班会的 Streamlit 文字冒险互动网页，适合教室投影使用。AI 担任游戏主持人（GM），围绕**期末诚信考试**与**正确成长观**推进剧情，全班可通过选项或自定义输入共同决策。

## 快速开始

```bash
pip install -r requirements.txt
streamlit run app.py
```

浏览器打开 `http://localhost:8501`，在侧边栏填写接口密钥即可开始。

## 在线部署（Streamlit Cloud）

1. 将本仓库推送到 GitHub
2. 打开 [share.streamlit.io](https://share.streamlit.io)，用 GitHub 登录
3. 选择本仓库，主文件填 `app.py`，点击 Deploy
4. 部署完成后会获得 `https://xxx.streamlit.app` 网址，可直接分享

> 接口密钥建议在 Streamlit Cloud 的 **Secrets** 中配置，不要写入代码。

## 详细说明

请参阅 [操作指南.md](操作指南.md)。

## 文件说明

| 文件 | 说明 |
|------|------|
| `app.py` | 主程序 |
| `requirements.txt` | Python 依赖 |
| `操作指南.md` | 完整操作指南 |
