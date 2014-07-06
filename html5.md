HTML5 - W3C仕様書の日本語訳
=====

####The section element < section > 

> The section element represents a generic section of a document or application. A section, in this context, is a thematic grouping of content. The theme of each section should be identified, typically by including a heading (h1-h6 element) as a child of the section element.

`<section>` は文書やアプリケーションの一般的な節(セクション)を表す。ひとつのセクションは、この文脈の中では、コンテンツをひとつの主題でグルーピングしたものである。それぞれのセクションの主題は、一般的に、セクション要素の子要素としてheadingタグ(見出し)が含まれることで判断すべきである。

> Examples of sections would be chapters, the various tabbed pages in a tabbed dialog box, or the numbered sections of a thesis. A Web site's home page could be split into sections for an introduction, news items, and contact information.

セクションは複数の章、タブ付きダイアログボックス内のページ、論文の番号付きセクションなどの例が挙げられるでしょう。
ウェブサイトのホームページは一つのイントロダクション、ニュース記事、コンタクト情報などでそれぞれセクションに分けられる。

> Note:Authors are encouraged to use the article element instead of the section element when it would make sense to syndicate the contents of the element.

注:要素の独立したコンテンツとして意味をなす場合は`<section>`ではなく`<article>`を使用することが推奨される。

> Note:The section element is not a generic container element. When an element is needed only for styling purposes or as a convenience for scripting, authors are encouraged to use the div element instead. A general rule is that the section element is appropriate only if the element's contents would be listed explicitly in the document's outline.

注:`<section>`要素は一般的なコンテナ要素(他の要素を包括するもの)ではない。スタイリング目的や装飾目的で要素が必要なときは`<div>`を使うべきである。  
要素の内容が文書のアウトライン(構造)に明示的に記載される時だけ、`<section>`要素を使うのが一般的なルールである。