+++
title = "Hugo New Article"
date = "2026-02-23T00:13:27+08:00"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = "Peter"
authorTwitter = "" #do not include @
cover = ""
tags = ["Hugo", "Github"]
keywords = ["教學", "靜態網站"]
description = ""
showFullContent = false
readingTime = true
hideComments = false
+++
 
## 建立新文章  

 **Step 1: 進入 Hugo 專案根目錄新增 `.md`**  

```bash
hugo new posts/<article_name>.md  

```

 **Step 2: 撰寫內容**  

用偏好的編輯器 (Text Editor, VS Code) 打開並編輯  

- **注意**：發表前要將 `draft` 設定為 `false`（例如：`draft: false` 或 `draft = false`）。  

 **Step 3: Preview (預覽)**  

```bash
hugo server -D  

```

 **Step 4: Push to GitHub**  

```bash
git add .   
git commit -m "commitment description"  
git push origin main  

```
