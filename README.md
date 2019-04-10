# Anguar CLI 專案切換至 StackBlitz 的瀏覽器書籤小工具

## 工具簡介

將存放在 GitHub 上的 Angular CLI 專案，移轉至 StackBlitz 線上快速執行。更多介紹請參考 Angular 官方部落格[這篇文章](https://blog.angular.io/run-angular-cli-repos-directly-in-your-browser-41332fd80901)。

## 安裝方式

1. 開啟瀏覽器，並打開瀏覽器的**書籤工具列**或**我的最愛列**：
   * Google Chrome 瀏覽器請按下 `Ctrl+Shift+B` 進行切換。
   * Internet Explorer 瀏覽器請點選主選單的 `[檢視]` / `[工具列]` / `[我的最愛列]` 進行切換。
2. 將以下超連結 (**Angular-StackBlitz**)，直接利用滑鼠拖曳到**書籤工具列**或**我的最愛列**上

* [Angular-StackBlitz](https://forum.angular.tw/)

3. 請你手動修改這個 **Angular-StackBlitz** 的超連結，並將超連結改成以下程式碼即可！


```js
javascript:!function(){var i=location.href;i.indexOf("//github.com/")>=0&&(location.href=i.replace(/github\.com/i,"stackblitz.com/github")),i.indexOf("//stackblitz.com/github/")>=0&&(location.href=i.replace(/stackblitz\.com\/github/i,"github.com"))}();
```

## 測試方式

1. 開啟 GitHub 上面的 Angular CLI Demo 專案 [https://github.com/aveferrum/angular-material-demo](https://github.com/aveferrum/angular-material-demo)
2. 點選上面安裝方式所建立的 **Angular-StackBlitz** 書籤
3. 網站就會轉換成 [https://stackblitz.com/github/aveferrum/angular-material-demo](https://stackblitz.com/github/aveferrum/angular-material-demo)
4. 反之亦然
