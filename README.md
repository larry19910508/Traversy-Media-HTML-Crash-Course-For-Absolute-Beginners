成果:
![image](https://hackmd.io/_uploads/BkBPOJ8La.png)

![image](https://hackmd.io/_uploads/r1GO_JI8T.png)

![UB1O30fR-EE-HD](https://hackmd.io/_uploads/rJlwAhBLa.jpg)

![image](https://hackmd.io/_uploads/H1U4o6SLp.png)
# Page Structure(HTML)
# Inline .vs Block Level Elements
![image](https://hackmd.io/_uploads/B1RUm0rI6.png)

# Tag Attributes
![image](https://hackmd.io/_uploads/Hy-N7RBI6.png)
顯示並且修改為 value
只顯示不修改為 placeholder

# HTML5 Semantic Tags
![image](https://hackmd.io/_uploads/B13d6CSLa.png)

# 關鍵字查詢
abbr
在 HTML 中，`<abbr>` 是表示縮寫的標籤。`<abbr>` 標籤用來標記縮寫或首字母縮略詞，並且通常與 `title` 屬性一起使用，提供縮寫的完整解釋或含義。

以下是 `<abbr>` 標籤的基本用法範例：

```html
<p>HTML <abbr title="HyperText Markup Language">HTML</abbr> 是一種標記語言。</p>
```

在這個例子中，"HTML" 是縮寫，而 `title` 屬性則提供了 "HyperText Markup Language" 這個完整的解釋，當使用者將滑鼠懸停在縮寫上時，會顯示這個完整解釋。這有助於提供更多的說明和上下文給使用者。

blockquote
在 HTML 中，`<blockquote>` 是表示區塊引用的標籤。這個標籤用來標示一個區塊內的文本是引用自其他來源的內容，通常用於引用長篇文字或外部來源的引述。

以下是 `<blockquote>` 標籤的基本用法範例：

```html
<blockquote>
  <p>引用的內容在這裡。</p>
  <footer>引用來源</footer>
</blockquote>
```

在這個例子中，`<blockquote>` 元素包含了被引用的內容（通常是一個段落），並使用 `<footer>` 元素標示引用的來源。這有助於提供更多的資訊給讀者，使其知道這段文字是引自其他來源的。

在實際應用中，你可以在 `<blockquote>` 中包含各種內容，包括多個段落、列表等，以呈現引用的內容。

cite
在 HTML 中，`<cite>` 元素用於表示對另一個文檔中的引用。通常，它被用來包裝對書籍、文章、電影、音樂等作品的引用，以指示這部分文本是對某個特定作品的引述。

以下是 `<cite>` 標籤的基本用法範例：

```html
<p>我最喜歡的書籍是 <cite>《1984》</cite>，它是由喬治·歐威爾（George Orwell）撰寫的。</p>
```

在這個例子中，`<cite>` 標籤用來標示作品的標題《1984》並指出這是喬治·歐威爾所撰寫的。這有助於區分正常文本和引用的作品，同時提供更多上下文信息。

請注意，`<cite>` 標籤本身並不會改變文本的外觀，它的目的是為了標記引用的內容。為了調整引用文本的外觀，你可能需要使用 CSS 或其他樣式設定。

form
在 HTML 中，`<form>` 元素用來定義一個 HTML 表單（form）。表單是用於收集或提交用戶輸入數據的交互性元素。`<form>` 元素可以包含各種輸入元素、選擇元素、按鈕、文本區域等，這些元素可以讓用戶輸入不同類型的數據。

以下是一個簡單的 `<form>` 元素的例子：

```html
<form action="/submit_form" method="post">
  <label for="username">使用者名稱：</label>
  <input type="text" id="username" name="username" required>

  <label for="password">密碼：</label>
  <input type="password" id="password" name="password" required>

  <button type="submit">提交</button>
</form>
```

在這個例子中，`<form>` 包含了兩個輸入框（一個用於使用者名稱，一個用於密碼）和一個提交按鈕。`action` 屬性指定了表單數據應該被提交的目標 URL，而 `method` 屬性指定了提交表單時使用的 HTTP 方法（在這個例子中是 POST 方法）。

表單的內容將被提交到指定的 URL，以便後端處理並進行相應的操作。在實際應用中，可能會使用 JavaScript 來進行表單的驗證和其他交互性操作。
<br>
select
在 HTML 中，`<select>` 元素用來創建下拉列表框，允許用戶從預定義的選項中選擇一個或多個選項。通常，`<select>` 元素與 `<option>` 元素一同使用，`<option>` 定義了下拉列表中的每個選項。

以下是一個簡單的 `<select>` 元素的例子：

```html
<label for="cars">選擇一輛車：</label>
<select id="cars" name="cars">
  <option value="volvo">沃爾沃</option>
  <option value="saab">紳寶</option>
  <option value="mercedes">奔馳</option>
  <option value="audi">奧迪</option>
</select>
```

在這個例子中，`<select>` 元素創建了一個下拉列表框，`id` 屬性用於標識這個元素，`name` 屬性指定了在表單提交時使用的名稱。`<option>` 元素定義了下拉列表中的每個選項，`value` 屬性指定了每個選項的值，而元素內的文本是顯示給用戶的選項標籤。

用戶可以通過單擊下拉列表框並選擇其中的一個選項。在提交表單時，選擇的值將被提交給後端處理。在前端，也可以使用 JavaScript 來動態修改下拉列表的選項，以實現更多的交互性。
<br>
label
在 HTML 中，`<label>` 元素用於定義表單元素的標籤。`<label>` 的主要目的是提供對相應表單元素的文字描述，這樣用戶就可以更容易地理解表單的內容。通常，`<label>` 元素與表單元素（如 `<input>`、`<select>`、`<textarea>` 等）一同使用，並透過 `for` 屬性關聯到相應的表單元素。

以下是一個使用 `<label>` 的例子：

```html
<label for="username">用戶名稱：</label>
<input type="text" id="username" name="username">
```

在這個例子中，`<label>` 的 `for` 屬性的值是相應表單元素的 `id`。這樣做的好處是，當用戶點擊標籤時，相應的表單元素就會自動獲得焦點，提高了用戶體驗。

使用 `<label>` 有助於提高表單的可訪問性，特別是對於視覺障礙的用戶。屏幕閱讀器等輔助技術可以使用 `<label>` 元素提供的信息，使用戶更容易理解表單的目的和如何填寫。
<br>
header
在 HTML 中，`<header>` 元素是用來表示文檔或區域的標題或標頭的容器。通常，它位於文檔或區域的頂部，包含一個或多個標題元素（如 `<h1>` 到 `<h6>`）或其他相關的標頭內容。`<header>` 可以包含 logo、導航鏈接、搜索框等與標頭相關的內容。

以下是一個簡單的例子，展示了如何使用 `<header>`：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>網頁標題</title>
</head>
<body>

<header>
    <h1>我的網站</h1>
    <nav>
        <ul>
            <li><a href="#home">首頁</a></li>
            <li><a href="#about">關於我們</a></li>
            <li><a href="#contact">聯繫我們</a></li>
        </ul>
    </nav>
</header>

<!-- 其他內容 -->

</body>
</html>
```

在這個例子中，`<header>` 包含了網站的標題 `<h1>` 和一個簡單的導航（`<nav>`）。

請注意，`<header>` 不僅僅用於整個網頁的標頭，還可以用於區域的標頭，比如 `<header>` 可以包含在 `<article>` 或 `<section>` 元素中，代表這部分的標頭。
<br>
nav
在 HTML 中，`<nav>` 元素用來定義網頁的導航區域。通常，這個導航區域包含一組連結，讓用戶可以快速地跳轉到網站的其他部分或其他相關頁面。

以下是一個簡單的 `<nav>` 使用例子：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>導航示例</title>
</head>
<body>

<nav>
    <ul>
        <li><a href="#home">首頁</a></li>
        <li><a href="#about">關於我們</a></li>
        <li><a href="#services">服務</a></li>
        <li><a href="#contact">聯繫我們</a></li>
    </ul>
</nav>

<!-- 其他內容 -->

</body>
</html>
```

在這個例子中，`<nav>` 包含了一個無序列表（`<ul>`），其中的每個列表項（`<li>`）包含一個超鏈接（`<a>`），這些超鏈接定義了網站的不同部分。當用戶點擊這些鏈接時，瀏覽器可能會導航到相應的區域或頁面。

`<nav>` 的使用可以幫助提高網站的可訪問性，讓用戶更容易找到並導航到所需的信息。
<hr>
題外:
1. 無序列表:
無序列表是 HTML 中用來表示項目沒有特定順序的一種列表。無序列表使用 `<ul>` 元素來定義，列表中的每個項目使用 `<li>` 元素表示。通常，無序列表的項目以符號（如圓點、方塊等）開頭，具體的樣式由瀏覽器或網站的樣式表定義。

以下是一個簡單的無序列表的 HTML 例子：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>無序列表示例</title>
</head>
<body>

<h2>水果</h2>

<ul>
    <li>蘋果</li>
    <li>香蕉</li>
    <li>橙子</li>
</ul>

</body>
</html>
```

在這個例子中，`<ul>` 定義了一個無序列表，其中包含三個項目（蘋果、香蕉、橙子）。每個項目使用 `<li>` 定義。瀏覽器會將這些項目以預設的方式呈現，通常是以圓點作為項目符號。但是，具體的呈現樣式可能會因瀏覽器和樣式表的不同而有所不同。
<br>
section
在 HTML 中，`<section>` 是一個用來標記文檔中的區塊或節的元素。它通常用於組織文檔的內容，將相關的內容組合在一起，以便更好地結構化頁面。

`<section>` 元素沒有固定的語義含義，它的具體含義取決於上下文和使用方式。通常，它被用來表示文檔中的一個主題或一個主題的一個部分。在一個頁面中，你可以有多個 `<section>`，每個都包含了相關的內容，例如文章的不同部分、頁面的不同章節等。

以下是一個簡單的使用 `<section>` 的 HTML 例子：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Section 示例</title>
</head>
<body>

<section>
    <h2>介紹</h2>
    <p>這是一個簡單的 HTML 示例，演示了如何使用 <code>&lt;section&gt;</code> 元素。</p>
</section>

<section>
    <h2>功能</h2>
    <p>這個示例用於展示 <code>&lt;section&gt;</code> 元素的基本功能。</p>
</section>

</body>
</html>
```

在這個例子中，有兩個 `<section>` 元素，分別包含了介紹和功能的相關內容。這有助於更好地組織和理解文檔的結構。
<br>
article
在 HTML 中，`<article>` 元素用於表示獨立的、完整的、可以獨立分發或重複使用的內容。通常，`<article>` 元素用來包裹一個獨立的新聞文章、博客帖子、論壇帖子或其他類似的內容單元。

`<article>` 元素的使用場景是那種可以獨立存在的內容，而不依賴於文檔的其餘部分。這意味著你可以單獨提取、分發或重複使用一個 `<article>` 區塊，而不會失去內容的完整性。

以下是一個簡單的使用 `<article>` 的 HTML 例子：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Article 示例</title>
</head>
<body>

<article>
    <h2>新聞標題</h2>
    <p>這是一個重要的新聞事件的內容...</p>
    <p>更多相關信息和詳情...</p>
</article>

</body>
</html>
```

在這個例子中，`<article>` 元素包裹了一個新聞文章的內容。這個 `<article>` 區塊可以獨立存在，而不需要依賴於文檔的其他部分。
<br>
aside
在 HTML 中，`<aside>` 元素用於標識一個與周圍內容關聯度較低的部分，通常表示的是一些附加信息、側邊欄、廣告、引用或其他類似內容。`<aside>` 的內容與文檔的主要內容相關，但可以被視為一個獨立的區塊。

以下是一個簡單的使用 `<aside>` 的 HTML 例子：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aside 示例</title>
</head>
<body>

<article>
    <h2>主要內容</h2>
    <p>這是一個主要的內容區塊...</p>
</article>

<aside>
    <h2>附加信息</h2>
    <p>這是一些附加的信息，可能是一個側邊欄、廣告或其他相關內容...</p>
</aside>

</body>
</html>
```

在這個例子中，`<aside>` 元素包含了一個標題和一些附加信息，這部分信息被視為主文檔的附屬內容，可能是側邊欄或其他相似的元素。`<aside>` 的內容可以被視為一個對主文檔的補充，而不是主要內容。
<br>
footer
在 HTML 中，`<footer>` 元素通常用於定義文檔或文檔的一個部分的頁腳（footer）。頁腳是一個容器，其中包含文檔的作者、版權信息、相關鏈接、地址等與文檔底部相關的內容。

以下是一個簡單的使用 `<footer>` 的 HTML 例子：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Footer 示例</title>
</head>
<body>

<article>
    <h1>文檔標題</h1>
    <p>這是文檔的主要內容...</p>
</article>

<footer>
    <p>© 2023 作者名稱。保留所有權利。</p>
    <p>地址：123 Main St, Cityville</p>
    <p>相關鏈接：<a href="privacy.html">隱私政策</a> | <a href="contact.html">聯繫我們</a></p>
</footer>

</body>
</html>
```

在這個例子中，`<footer>` 元素包含了一些版權信息、地址和相關鏈接。這些信息被視為文檔底部的內容，通常用於提供有關文檔的附加信息。`<footer>` 通常是整個文檔的最底部，但可以包含在其他元素中，如 `<article>` 或 `<section>`，以區分文檔的不同部分。
<br>

# 課程解釋
這段文字主要是一位網頁開發者在教授初學者如何開始學習網頁設計和開發的內容。以下是主要內容的分段和一些關鍵字：


這位網頁開發者歡迎觀眾進入他的「Web Development for Absolute Beginners」系列的第一堂課。這個系列針對任何想要學習基本網頁設計和開發的人，並且不需要任何先備知識。課程將持續進行，每個視頻將聚焦於不同的主題。此視頻的內容將專注於 HTML，然後可能涉及到 CSS 和 JavaScript。同時，他還計劃教授如何將網站上傳到互聯網。


在開始之前，他提到一些事項，強調這是針對初學者的系列，對於已經具有一定經驗的訂閱者，可能這些內容都很基礎。他解釋了他為什麼創建這個系列，以及在這個系列中不會一直保持對高級程序員的關注。同時，他提到本視頻中將很少使用 CSS，而主要集中於 HTML 語法。


介紹 HTML（Hypertext Markup Language）是用於創建網頁和文檔的標記語言。他強調 HTML 不是一種編程語言，而是用於顯示和格式化網頁元素的標記語言。他解釋了 HTML 與編程語言的區別，並提到 HTML 是 Web 的基礎，即使在複雜的網站中也會輸出 HTML。


作者提到 HTML 文件的基本結構，包括 doctype、html、head 和 body 等標籤。他解釋了這些標籤的作用，並提到 head 中通常包含頁面標題、CSS 文件和 JavaScript 文件等元數據。同時，他展示了一個簡單的 HTML 頁面結構的示例。


介紹了 doctype，並展示了不同版本的 doctype，但指出他們將專注於 HTML5。然後，作者展示了如何在 Sublime Text 中創建 HTML 文件，並提供了一個基本的 HTML 模板。


作者開始講解 HTML 標籤，並介紹了標題標籤（h1-h6）和段落標籤（p）。他展示了如何使用 Sublime Text 中的快捷方式生成 dummy text，並演示了標題和段落的效果。


討論了 HTML 中的強調標籤（strong）和強調標籤（em），以及它們的預設樣式。同時，作者展示了如何使用連結標籤（a）創建超連結，並解釋了 href 和 target 屬性的作用。


介紹了 HTML 中的層次結構，包括塊級元素和內聯元素的區別。作者展示了如何使用無序列表（ul）和列表項（li）創建項目列表，同時提到這些元素的默認樣式。

這只是對這段文本的簡單摘要，
這段影片教學涵蓋了HTML的基本標籤和元素。以下是主要內容的分段：

1. **HTML基本結構：**
   - HTML檔案的起始部分通常包括`<!DOCTYPE html>`聲明和`<html>`標籤。
   - `<head>`標籤內包含了`<title>`標籤，用於設定網頁標題。

2. **文字標籤：**
   - 使用`<h1>`到`<h6>`標籤表示標題，數字表示標題的層級。
   - 段落使用`<p>`標籤。

3. **超連結：**
   - 使用`<a>`標籤創建超連結，`href`屬性指定目標URL。

4. **清單：**
   - 無序清單使用`<ul>`和`<li>`標籤，有序清單使用`<ol>`和`<li>`標籤。

5. **表格：**
   - 使用`<table>`、`<thead>`、`<tbody>`、`<tr>`、`<th>`和`<td>`標籤創建表格。

6. **表單：**
   - 使用`<form>`標籤創建表單，包括`<input>`、`<textarea>`和`<select>`等表單元素。

7. **圖片：**
   - 使用`<img>`標籤嵌入圖片，可使用`src`、`alt`、`width`和`height`等屬性。

8. **引用和縮寫：**
   - 使用`<blockquote>`標籤表示引用，`<abbr>`標籤表示縮寫。

9. **HTML5語意標籤：**
   - 引入HTML5新增的語意標籤，如`<header>`、`<nav>`、`<section>`、`<article>`、`<aside>`和`<footer>`，以更清晰地結構網頁。

10. **搜尋引擎優化（SEO）：**
    - 使用`<meta>`標籤添加`description`和`keywords`，有助於搜尋引擎了解網頁內容。

11. **頁面連結：**
    - 透過`<a>`標籤創建連結，讓使用者可以在不同頁面間切換。

12. **CSS樣式：**
    - 使用`<style>`標籤內嵌CSS，提供簡單的樣式，例如文字置中、背景色等。

13. **JavaScript連結：**
    - 透過`<script>`標籤連結JavaScript檔案，使網頁具備動態功能。

影片中提到的HTML基礎和語法規則能夠協助建立靜態網頁結構，並奠定後續學習CSS和JavaScript的基礎。建議觀眾在深入學習前端開發的同時，注意掌握HTML的基本概念。

