# DTML (Dot Text Markup Language)
### DTML is a coding language that I am creating that mimics HTML in a minimalistic way. The key is below:

##### (HTML = DTML)

Note: CSS and JavaScript are the same in HTML and DTML

```
<p style="color:red" title="tooltip">foo</p> = ;[tooltip][color=red]-foo;

<h1 id="iD">foo</h1> = ;1[id=iD]-foo;

<title>foo</title> = ;title-foo;

<head>cont</head> = :head-cont:

<a href="https://l-i.nk">foo</a> = ;link[url=https://l-i.nk]-foo;

<img src="/img/foo.png" alt="an alt" width="500" height="600"> = ?img[img=/img/foo.png][alt=an alt][w=500][h=600]?

<div style="background-image: url('img.png');" class="tag">cont</div> = :[class=tag][background.image=/img/img.png]-cont:

<style>css!</style> = :css-css!:

<script>javascript</script> = :js-javascript:

<br> = ?lb?

<!--a note--> = :;a note;:

<!DOCTYPE HTML> = :[dtml]:

<html lang="en-US">foo
</html> = :code[lang=en.us]-foo
          :end

<body>foo</body> = :main-foo:

<footer>foo</footer> = :foot-foo:

<hr> = ?div?

<meta charset="UTF-8"> = !meta[char=UTF-8]!

<meta name="viewport" content="width=device-width, initial-scale=1.0"> = !meta[port][w=device.w][scale=1.0]!

<pre>foo</pre> = !form-foo!

<b>bold</b> = **bold**

<i>italic</i> = *italic*

<mark>mark</mark> = #mark#

<small>tiny</small> = &tiny&

<del>strike</del> = ~strike~

<ins>underline</ins> = _underline_

<sub>subscript</sub> = \subscript\

<sup>super</sup> = ^super^

<q>quote</q> = ;"-quote;

<blockquote cite="https://website.com">block</blockquote> = ;""-;

<abbr title="Abbreviation">ABB.</abbr> = ;#[Abbreviation]-ABB.;

<address>foo st.</address> = ;@-foo st.;

<cite>Foo</cite> = ;*-Foo;

<bdo dir="rtl">oof</bdo> = ;[dir=rt.lft]-oof;

<link rel="icon" href="/img/favicon.ico"> = ?icon-/img/favicon.ico?

<link rel="stylesheet" href="styles.css"> = ?stylesheet-styles.css?

<table>cont</table> = ?tbl-cont?

<tr>cont</tr> = ?row-cont?

<th>foo</th> = ?tbl.head-foo?

<td>foo</td> = ?tbl.item-foo?

<ul>cont</ul> = ?list.uo-cont?

<ol>cont</ol> = ?list.or-cont?

<dl>cont</dl> = ?list.desc-cont?

<li>foo</li> = ?list.item-foo?

<dt>foo</dt> = ?list.desc.item-foo?

<dd>foo</dd> = ?list.desc.desc-foo?

<span>foo</span> = ;+-foo;

<iframe src="https://url.com"></iframe> = ?embed[link=https://url.com]?

<base href="https://mywebsite.com/img/" target="_blank"> = !base[link=https://mywebsite.com/img/][tab=blank]!

<nav>cont</nav> = ;nav-cont;

<header>cont</header> = ;head-cont;

<aside>cont</aside> = ;aside-cont;

<details>cont</details> = ;det-cont;

<summary>cont</summary> = ;summ-cont;

<code><p>foo</p></code> = ;code-<p>foo</p>;

<kbd>cmd+q</kbd> = ;kbd-cmd+q;

<samp>ERROR</samp> = ;smp-ERROR;

<var>X</var> = ;var-X;

&copy; = ;=copy;

<form>Name here...<input type="text" name="name"></form> = ?form-;input[name][type=text]-Name here...;?

<form action="/actionpage.html"><input type="radio" name="foo" value="foo" checked>foo<input type="submit" value="Submit"></form> = ?form[do=/actionpage.html];input[foo][val=foo][type=radio]foo;?

<video autoplay><source src="movie.mp4" type="video/mp4">Your browser does not support the video tag</video> = ?vid.auto[src=movie.mp4][type=video/mp4]-Your browser does not support the video tag?

```

## Example:

```
:[dtml]:
:code-
:head-
;title-Foo;
:
:main-
:-
;1-Foobar;
:
:-
;-Foo?lb?Bar;
:
:
:foot-
;6-©2019 Mr. Foo;
:
:end
```
