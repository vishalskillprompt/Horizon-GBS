# Images

**Code**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Images</title>
  </head>
  <body>
    <div>
      <h2>Without width or height</h2>
      <img
        src="https://th.bing.com/th/id/R.6e4e17d0436c9eb8505ecc7c3bef9cb1?rik=ZZcEn9zIIuCH4g&pid=ImgRaw&r=0"
      />
    </div>
    <div>
      <h2>With width or height</h2>
      <img
        src="https://th.bing.com/th/id/R.6e4e17d0436c9eb8505ecc7c3bef9cb1?rik=ZZcEn9zIIuCH4g&pid=ImgRaw&r=0"
        width="600px"
        height="300px"
      />
    </div>

    <div>
      <span>
        <h2>Inside picture tag</h2>
        <p>
          (for selecting different version of same image depending on the
          device)
        </p>
      </span>
      <picture>
        <source
          srcset="
            https://f.hubspotusercontent10.net/hubfs/3024469/logo-2582748_1280.png
          "
          media="(max-width: 600px)"
        />
        <img
          src="https://th.bing.com/th/id/R.7ad4bc9baf4d3ad38bbc1cdf6262e6de?rik=%2f6KsCAQfr5QhKQ&pid=ImgRaw&r=0"
          width="600px"
          height="300px"
        />
      </picture>
    </div>
  </body>
</html>
```

**Output**

![images output](./assets/images-output.png)

## Other media tags

- Audio
- Video
