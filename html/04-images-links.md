# Links (\<a> tag)

- It is used to link web pages.
- **Internal link**: Link to another page in same website.
- **External link**: Link to page outside the website.

## Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Block and inline elements</title>
  </head>
  <body>
    <div>
      <a href="/">
        <img
          src="https://www.skillprompt.com/assets/company_logo/logo.png"
          width="100%"
          height="500px"
        />
        Home (Internal link)
      </a>
    </div>
    <hr />
    <div>
      <a href="#about">Go to About section (Internal link)</a>
    </div>
    <hr />
    <div>
      <a href="https://www.linkedin.com/">
        <img
          src="https://th.bing.com/th/id/R.ba6627a6660203499fae0a1eb626a8ab?rik=OSCyHWn1bpoRuQ&pid=ImgRaw&r=0"
          width="100%"
          height="800px"
        />
        LinkedIn (External link)
      </a>
    </div>
    <hr />
    <div id="about">
      <h3>This is about us section.</h3>
      <p>We are learning HTML links.</p>
      <img
        src="https://i.ytimg.com/vi/eRAI3Nm32OQ/maxresdefault.jpg"
        width="100%"
        height="800px"
      />
    </div>
  </body>
</html>
```
