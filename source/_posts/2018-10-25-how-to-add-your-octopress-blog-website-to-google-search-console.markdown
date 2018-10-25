---
layout: post
title: "如何使Octopress website在Google搜索到"
date: 2018-10-25 23:25:25 +0800
comments: true
categories: [Octopress]
---

1. 登入[Google search console](https://search.google.com/search-console/welcome)
2. 提交Blog的Domain name```http://[username].github.io/```
3. 下載驗證的html檔案
4. 放到```octopress/source```目錄下
5. 建置及部署
   
   ```
   rake gen_deploy
   ```
   
6. 回到Google search console，點擊驗證，完成