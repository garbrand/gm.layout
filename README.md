# gm.layout

Simple CSS package providing CSS boilerplate.

## reset.css
Resets the following properties of **all** DOM elements:
- margin
- padding
- outline

It also sets box sizing model to border box.

## layout.css
Simple helper classes for application positioning.

Example:
```html
<nav id="toolbar" class="pinned top sides" style="height: 3em"></nav>
<section id="viewport" class="pinned bottom sides" style="top: 3em">
	<aside id="mailboxes" class="pinned height left" style="width: 25%"></aside>
	<section id="message" class="pinned height right" style="width: 75%"></section>
</section>
```

## grid.css
A percentage based 12 column grid, see grid.css.

The CSS expects a containing node for each row. There is a class for all possible grid columns a column can span.

Example:
```html
<section class="row">
    <section class="spans-4">I span four vertical grid units.</section>
    <section class="spans-8">So I span eight vertical units to add up to 12.</section>
</section>
```
