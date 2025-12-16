# HTML - Level 1 - Part A

## What is HTML?

- Hyper Text Markup Language
- Structure & Formatting

## HTML Elements

- Standard Elements that browser recognizes:

1. Paragraph
2. Heading
3. Image

The component used to structure the website are called HTML tags.

## HTML Tags

A container for some content and other tags.

`<p>This is a paragraph</p>`

`<p>` = Opening Tag
`</p>` = Closing Tag
This is a paragraph = Content

`Opening Tag + Content + Closing Tag = HTML Element`

## Hello World

```html
<p>Hello World!</p>
<p>I'm Rahul</p>
<p><b>Apna College</b></p>
```

## Paragraph Element

The `<p>` HTML element represents a paragraph.

```html
<p>This is my first paragraph. This is my second paragraph.</p>

<p><b>This is my third paragraph.</b></p>
```

## Heading Elements

The `<h1>` to `<h6>` HTML elements represents six levels of section headings.

`<h1>` is the highest section level and `<h6>` is the lowest.

**Note:**

- Usually, we have only one h1 tag in a webpage.

```html
<h1>Avengers</h1>
<h2>Iron Man</h2>
<p>This is a paragraph.</p>
<h2>Thor</h2>
<p>This is a paragraph.</p>
<h2>Hulk</h2>
<p>This is a paragraph.</p>
```

## Practice Qs 1

```html
<h1>Avengers</h1>
<h2>Iron Man</h2>
<p>Also goes by the name <b>Tony Stark</b></p>
<h2>Captain America</h2>
<p>Also goes by the name <b>Steve Rogers</b></p>
<h2>Hulk</h2>
<p>Also goes by the name <b>Bruce Banner</b></p>
```

## HTML Boilerplate

This is the standard format or skeleton of writing HTML code.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My First Page</title>
  </head>

  <body>
    <p>Hello World!!</p>
  </body>
</html>
```

`<!DOCTYPE html>` = HTML version 5
`<html></html>` = Root tag
`<head></head>` = It contains meta data.
`<title></title>` = It contains title of the tab.
`<body></body>` = It contains content.
