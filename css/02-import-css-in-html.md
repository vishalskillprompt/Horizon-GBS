# How to import CSS in HTML ?

- CSS can be written in three different ways in HTML.

### Inline

- Create index.html file

**Code**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inline CSS</title>
  </head>
  <body>
    <div style="background-color: antiquewhite">
      <h1 style="color: blueviolet">How to write inline CSS?</h1>
    </div>
  </body>
</html>
```

**Output**
![output](./assets/inline_output.png)

### Internal

- Create index.html file
- Write CSS in \<style> tag

**Code**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Internal CSS</title>
    <style>
      div {
        background-color: antiquewhite;
      }
      h1 {
        color: blueviolet;
      }
    </style>
  </head>
  <body>
    <div>
      <h1>How to write internal CSS?</h1>
    </div>
  </body>
</html>
```

### External

- Create index.html file
- Create app.css file
- External css file can be imported in HTML file using \<link> tag
- rel attribute is used to specify the relation between the current document and the document being imported

**Code**

- Code for index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>External CSS</title>
    <link rel="stylesheet" href="./app.css" />
  </head>
  <body>
    <div>
      <h1>How to write external CSS and import it in HTML file?</h1>
    </div>
  </body>
</html>
```

- Code for app.css

```css
div {
  background-color: antiquewhite;
}
h1 {
  color: blueviolet;
}
```
