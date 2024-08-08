# Styling an image element

**Code**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Styling an image</title>
    <style>
      #backgroundColor {
        background-color: rgb(229, 132, 132);
        height: 500px;
        color: white;
        font-size: 50px;
        text-align: center;
        padding: 15px;
        opacity: 0.9; /* 0.9 means ninety percent */
      }

      #backgroundImage {
        background-image: url("https://images.pexels.com/photos/11035386/pexels-photo-11035386.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1");
        height: 900px;
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
      }
      body {
        background-color: purple;
      }

      img {
        border-radius: 100%;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 400px;
        height: 400px;
      }

      * {
        margin: 0;
      }
    </style>
  </head>
  <body>
    <div id="backgroundColor">
      <h1>hey, let's learn to style images !!</h1>
    </div>
    <div id="backgroundImage">
      <img
        src="https://images.pexels.com/photos/943096/pexels-photo-943096.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
        alt=""
      />
    </div>
  </body>
</html>
```

**Output**

![styling image](./assets/styling-image-output.png)
