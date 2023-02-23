# HTML筆記
## How to use
node server.js will open a server in port 8080 
you can acess with 127.0.0.1/dir
## 基本觀念
```
<tag-name>Content</tag-name>
```
## 基礎範例
ex1.html:
```html
<p>Hello World</p>
```
就可以顯示Hello World這段文字
## 屬性
ex2.html:
```html
<p class="center">Hello World</p>
```
## 基本架構
### 名詞介紹
|名稱     | 功能意義 |
| ----------- | ----------- |
| ```<!DOCTYPE html>```      | 告訴檔案編輯模式      |
| img 的alt   | (alternative) 這個屬性。在網頁瀏覽者無法正確看到圖片時 提示文字    |
|```<head></head>```|裡面放的是你想涵括的重要資訊，但不會顯示於網頁瀏覽者眼前的。例如，顯示於搜尋結果的關鍵字、頁面說明*、*CSS、字元實體集|
|```<body></body>```|所有會顯示於網頁瀏覽者眼前的內容|
|```<meta charset="utf-8">```|編碼設定|
|```<title></title>```|標題設定|
### 範例
ex3.html
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <img src="images/Google-Logo.png" width="200" alt="My test image">
  </body>
</html>
```
## 文字類
### 文件標題 (heading)
ex4.html
```html
<h1>My main title</h1>
<h2>My top level heading</h2>
<h3>My subheading</h3>
<h4>My sub-subheading</h4>
```
### 段落 (paragraph)
ex5.html
```html
<p>This is a single paragraph</p>
```
### 清單顯示(list)
#### 名詞介紹
|名稱     | 功能意義 |
| ----------- | ----------- |
|ul(Unordered lists)|無順序|
|ol(ordered lists)|有順序|
#### 範例
ex6.html
```html
<html>
    <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
<p>At Mozilla, we’re a global community of</p>
<ul>
  <li>technologists</li>
  <li>thinkers</li>
  <li>builders</li>
</ul>
<ol>
  <li>technologists</li>
  <li>thinkers</li>
  <li>builders</li>
</ol>
<p>working together ... </p>
</html>

```