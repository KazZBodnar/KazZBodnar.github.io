# DTML (Dot Text Markup Language) (WIP!)
#### DTML is a coding language that I am creating that mimics HTML in a minimalistic way. The key is below:

###### (HTML = DTML)
```
<p>foo</p> = ;-foo;

<h1>foo</h1> = ;1-foo;

<title>foo</title> = ;title-foo;

<head>cont</head> = :head-cont:

<a href="https://l-i.nk">foo</a> = ;link[url=https://l-i.nk]-foo;

<img src="/img/foo.png" alt="an alt"> = ?img[img=/img/foo.png][alt=an alt]?

<div>cont</div> = :-cont:

<style>css!</style> = :css-css!:

<script>javascript</script> = :js-javascript:

<br> = ?lb?

/!--a note--/ = :;a note;:

<!DOCTYPE HTML> = :[dtml]:

<html>foo
</html> = :code-foo
          :end

<body>foo</body> = :main-foo:

<footer>foo</footer> = :foot-foo:

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
;-Foo:lb:Bar;
:
:
:foot-
;6-©2019 Mr. Foo;
:
:end
```
