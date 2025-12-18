# HTML - Level 2

## Inline vs Block

**Block Elements**

- Takes up the full width available
- Start from new line

**Inline Elements**

- Takes up only necessary width

**Am i inline or block?**

- Heading Element = Block
- Paragraph Element = Block
- Anchor Tag = Inline
- Image Element = Inline

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inline Block</title>
  </head>

  <body>
    <h1>Hello World!</h1>
    <h1>Apna College</h1>

    <p>Hello World!</p>
    <p>Apna College!</p>

    <a href="www.google.com">Google</a>
    <a href="www.facebook.com">Facebook</a>
    <a href="www.youtube.com">Youtube</a>

    <img
      src="https://i.pinimg.com/736x/17/54/27/175427784715922a7d1cedd638bb7c2f.jpg"
      height="500px"
    />
    <img
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVIayST3A2OotDBo4upwA2WCKKC1VZvmxGiw&s"
      height="200px"
    />
  </body>
</html>
```

## Div Element

Div is a container used to hold other HTML elements or group elements together.

It is a block element.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Div Element</title>
  </head>

  <body>
    <div>
      <a href="www.google.com">Google</a>
      <a href="www.youtube.com">Youtube</a>
    </div>
    <a href="www.facebook.com">Facebook</a>
  </body>
</html>
```

## Span Element

Span is also a container used to hold other HTML elements or group elements together.

It is a inline element.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Span Element</title>
  </head>

  <body>
    <span>
      <a href="www.google.com">Google</a>
      <a href="www.youtube.com">Youtube</a>
    </span>
    <a href="www.facebook.com">Facebook</a>
  </body>
</html>
```

## Hr Tag

Horizontal Rule Element

`<hr>`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Hr Tag</title>
  </head>

  <body>
    <p>Hi, I am Rahul.</p>
    <p>I am a web developer.</p>
    <hr />
    <p>I learn on Apna College.</p>
    <p>I love coding.</p>
  </body>
</html>
```

## Sub & Sup Tag

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sub Sup Tag</title>
  </head>

  <body>
    <h1>a<sup>2</sup></h1>
    <h1>H<sub>2</sub>O</h1>
  </body>
</html>
```

## Practice Qs 4

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Practice Qs 4</title>
  </head>

  <body>
    <h1>
      Pythagoras theorem says a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>
    </h1>

    <h1>Formula for glucose is C<sub>6</sub>H<sub>12</sub>O<sub>6</sub></h1>
  </body>
</html>
```

## Semantic Markup

It relates to the meaning of content.

- Semantic Tags

  - `<h1>`
  - `<p>`

- Non-Semantic Tag
  - `<div>`
  - `<span>`

**Need?**

- Code becomes meaningful.
- Structured Layout.
- SEO friendly.
- Screen Reader + UX improved.

## Semantic Tags

`<header>`
`<main>`
`<footer>`
`<nav>`
`<section>`
`<article>`
`<aside>`

## Practice Qs 5

- Add semantic tags in portfolio project.

## HTML Entities

- An HTML entity is a piece of text that starts with ampersand `&` and ends with `;`.

- Used to display reserved characters (which would otherwise be interpreted as HTML code) and invisible character (like space).

- Can also use in place of characters that are difficult to type with a standard keyboard.

- Browser interprets them and renders correct character.

`&lt;` = less than
`&gt;` = greater than
`&quot;` = quotes
`&amp;` = quotes

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML Entities</title>
  </head>

  <body>
    <h1>a&lt;b</h1>
    <p>Apna &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; College</p>

    <h1>&hearts;</h1>

    <p>a&lt;b</p>
    <p>a&gt;b</p>
    <p>a&amp;b</p>
    <p>a&quot;b&quot;</p>
  </body>
</html>
```

## Practice Qs 6

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Practice Qs 6</title>
  </head>

  <body>
    <h1>The sky is cloudy &#9729; &amp; it will rain &#9748; today.</h1>
  </body>
</html>
```

## Emmets

Visit emmet.io