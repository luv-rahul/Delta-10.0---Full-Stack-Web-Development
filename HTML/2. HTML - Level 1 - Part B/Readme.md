# HTML - Level 1 - Part B

## Lists in HTML

##### Unordered List

```html
<ul>
  <li>Bread</li>
  <li>Butter</li>
  <li>Jam</li>
</ul>
```

##### Ordered List

```html
<ol>
  <li>Bread</li>
  <li>Butter</li>
  <li>Jam</li>
</ol>
```

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lists in HTML</title>
  </head>

  <body>
    <ul>
      <li>Bread</li>
      <li>Butter</li>
      <li>Tea</li>
    </ul>

    <ol type="a">
      <li>Bread</li>
      <li>Butter</li>
      <li>Tea</li>
    </ol>
  </body>
</html>
```

## HTML Attributes

Attributes are used to add more information to the tag.

`<html lang="en">`
`<ol type="a">`

## Anchor Element

Used to add links to you page.

`<a href=""https://www.google.com/>Google</a>`

href = HyperText Reference

Absolute link: Link on Internet
Relative link: Link on local system

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Anchor Element</title>
  </head>

  <body>
    <a href="https://www.google.com/">Google</a>
    <a href="https://www.netflix.com/">Netflix</a>
  </body>
</html>
```

## Image Element

Used to add image to your page.

`<img src="image.png" alt=""Random Image>`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Image Element</title>
  </head>

  <body>
    <img src="./spiderman.jpeg" alt="Spiderman" width="100%" />
    <img
      src="https://images7.alphacoders.com/710/thumb-1920-710793.jpg"
      alt="Spiderman"
      width="100%"
    />
  </body>
</html>
```

## Practice Qs 2

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Practice Qs 2</title>
  </head>

  <body>
    <h1>List of Fruits</h1>
    <ul>
      <li>
        Apple
        <a
          href="https://www.collinsdictionary.com/images/full/apple_158989157.jpg"
          >see an apple</a
        >
      </li>
      <li>
        Orange
        <a
          href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSE9fidqkhYH7A33z-78-glQDzVRTjl-UwVrg&s"
          >see an orange</a
        >
      </li>
      <li>
        Mango
        <a
          href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIZsfkc2zDCA423IfWyeg_FaRvFs_LyLeMUw&s"
          >see a mango</a
        >
      </li>
    </ul>
  </body>
</html>
```

## More HTML Tags

##### Br Tag

Used to add line breaks to your page
`<br>`

##### Bold, Italic and Underline Tag

Used to highlight text in your page.

```html
<b>Bold</b>
<i>Italic</i>
<u>Underline</u>
```

##### Comments in hTML

This is part of code that should not be parsed.

`<!--This is a HTML comment-->`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>More HTML Tags</title>
  </head>

  <body>
    <!-- This is a poem in HTML -->
    <p>
      Twinkle Twinkle <br />
      little star <br />
      How i wonder <br />
      what you are
    </p>
    <p>
      <b>Twinkle Twinkle</b> <br />
      <i>little star</i> <br /><u> How i wonder</u> <br />
      what you are
    </p>
  </body>
</html>
```

## Is HTML Case Sensitive?

HTML is non-case sensitive.
`<P>Hello World</p>`

## Practice Qs 3

- Make your PortFolio Project.
