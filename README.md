# Adobe Portfolio 圖片按鈕

公開頁：https://fang2027.github.io/portfolio-buttons/

## 修改內容
開啟 index.html，找「按鈕內容設定」，三組依序對應左、中、右按鈕。
- title：圖片下方的標題。
- image：一般圖片的公開 HTTPS 直連網址。
- hoverImage：滑鼠移入後顯示的圖片網址；留空則保持原圖。
- link：點擊後要前往的頁面網址；留空則無連結。

只改引號內的文字，保留引號與逗號。
在 GitHub 編輯 index.html 並 Commit changes 後，等待 Pages 部署完成再重新整理。
本頁不使用 GAS 或試算表；原 Google 試算表的修改不會影響本頁。

## Adobe Portfolio 嵌入碼
```html
<iframe src="https://fang2027.github.io/portfolio-buttons/" width="100%" height="400" frameborder="0" title="作品導覽"></iframe>
```
桌機三張並排；窄版保持單列左右滑動。外層高度先設 400，標題變長時再調整。
點擊另開分頁。移入圖片載入成功後淡入，失敗時保持原圖；觸控裝置顯示一般圖片。
目前三組 hoverImage 都留空，與遷移時的 GAS 設定一致。
