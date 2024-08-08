# Block and Inline

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Block and Inline</title>

    <style>
      .container {
        border: 2px solid red;
        margin: 20px;
      }

      #inline {
        display: inline;
        margin: 10px 20px;
      }

      #inline-block {
        display: inline-block;
        margin: 10px 20px;
      }

      #block {
        display: block;
        margin: 10px 20px;
      }
    </style>
  </head>
  <body>
    <div>
      <h1>Block and Inline Elements</h1>

      <div class="container" id="inline">i am inline</div>
      <div class="container" id="inline-block">I am inline block</div>
      <div class="container" id="block">I am a block</div>
    </div>
  </body>
</html>
```

# Flex

### Properties

- display: flex
- flex direction: row, column
- justify-content: left, center, right, space-around, space-evenly
- align-items: center, start, end
  -flex-wrap: wrap, nowrap

# Grid

- Layout system with rows and columns
- Properties to cover:

  - display
  - gap
  - grid-template-columns
  - grid-template-rows
  - grid-column-start
  - grid-column-end
  - grid-row-start
  - grid-row-end

### Output

- ![Grid output](./assets/grid-output.png)

# Position

- Get elements out of the flow of document

### Properties

- position
- left
- right
- top
- bottom

### Image

![image](./assets/grid-output.png)

### Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Grid</title>
    <style>
      .grid-container {
        display: grid;
        gap: 10px;
        grid-template-columns: 1fr 3fr 1fr;
        grid-template-rows: 80px 5fr 3fr 2fr;
      }

      .grid-item {
        padding: 10px;
        border: 2px solid red;
      }

      .header {
        grid-column-start: 1;
        grid-column-end: 4;
      }

      .menu {
        grid-row-start: 2;
        grid-row-end: 4;
      }

      .main {
        grid-row-start: 2;
        grid-row-end: 4;
      }

      .right {
        grid-row-start: 2;
        grid-row-end: 4;
      }

      .footer {
        grid-column-start: 1;
        grid-column-end: 4;
      }

      .chat-container {
        border: 2px solid red;
        background-color: blueviolet;
        width: 50px;
        height: 50px;
        border-radius: 100%;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <div class="grid-container">
      <div class="grid-item header">header</div>
      <div class="grid-item menu">menu</div>
      <div class="grid-item main">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim vitae
          corrupti rem! A, optio modi aut quos nobis eos labore cumque quis
          dolores, autem quibusdam perspiciatis minus blanditiis ratione
          deserunt.
        </p>
      </div>
      <div class="grid-item right">right</div>
      <div class="grid-item footer">footer</div>
    </div>
    <div class="chat-container">
      <p>C</p>
    </div>
  </body>
</html>
```

### Questions

- make the header stick on top when scrolling
- make the chat icon stick at the bottom right corner
