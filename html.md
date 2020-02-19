### HTML

- HTML has elements or "tags" <h1></h1>
- There's usually a "pair of tags, except for elements that cannot have "children" like <img /> or <input />

### tags
```html
<div>: general wrapper element (by default display is:block)

<span>: wrapper for some text (display:inline-block)

<img>: has a "src"

<header>

<main>

<a>: link with a "href" prop

<p>: paragraph

<select>



```
### form elements
```html
<form>: wraps around a bunch of inputs, and collects their data. It has an "onSubmit" prop

<input />: can have a "type" of "text", "number", "checkbox", "radio"

<button>: a button of type="submit" within a form will submit that form
```
### props?
There are built-in props that are standard to HTML elements (like onClick, value, or src)... but you can also add custom props to your own elements

### React vs HTML
- React Elements (or "components") always start with an Uppercase letter
- React props are always camelCase, while in HTML they are all lowercase

<ReactComponent>
    <div></div>
</ReactComponent>

{props.children}