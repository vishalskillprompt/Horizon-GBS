### 2. How to import CSS in HTML ?

- CSS can be written in three different ways in HTML.

### 2.1 Inline

- Create index.html file

**Code**

```html
<html lang="en">
  <head>
    <title>Inline CSS</title>
  </head>
  <body>
    <div style="background-color: antiquewhite; padding-top: 10px">
      <p style="color: blueviolet">How to write inline CSS?</p>
    </div>
  </body>
</html>
```

**Output**
![output](./assets/inline_output.png)

### 2.2 Internal

- Create index.html file
- Write CSS in \<style> tag

**Code**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Internal CSS</title>
    <style>
      #div1 {
        color: red;
      }
    </style>
  </head>
  <body>
    <div>
      <h1>How to write internal CSS?</h1>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Id, ratione
        eius consectetur, voluptatibus tenetur amet doloremque quisquam beatae
        debitis distinctio possimus. Quia, nostrum, iure doloremque cum corporis
        libero alias accusamus repellat, amet fugiat molestias deserunt in
        magni. Suscipit autem animi, voluptate excepturi aliquam molestiae harum
        quaerat. Soluta et modi ea, dolor dolores nobis id perspiciatis dolorum
        dolore voluptas harum, sapiente nisi, excepturi ducimus tenetur dolorem
        molestias at consequuntur nihil sit odio commodi. Beatae provident
        aliquid reprehenderit eum porro? Molestias necessitatibus voluptates
        totam iste in ad dolorum nobis corrupti, quas dicta dolor similique
        error libero velit veritatis soluta saepe asperiores fuga.
      </p>
      <div id="div1">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Alias,
        eligendi.
      </div>
      <button>Submit</button>
    </div>
  </body>
</html>
```

### 2.3 External

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
