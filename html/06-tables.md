### 1. Tables

### Table tags

- \<table>: define the table
- \<tr>: define a row
- \<th>: define a table header
- \<td>: define a table cells data
- \<thead>: define a header section
- \<tbody>: define a body section
- \<tfoot>: define a footer section

**Code**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tables</title>
  </head>
  <body>
    <table border="1">
      <thead>
        <tr>
          <th>S.N</th>
          <th>Item</th>
          <th>Quantity</th>
          <th>Rate</th>
          <th>Amount</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Apple</td>
          <td>2</td>
          <td>200</td>
          <td>400</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Mango</td>
          <td>2</td>
          <td>100</td>
          <td>200</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td></td>
          <td>Total</td>
          <td>4</td>
          <td></td>
          <td>600</td>
        </tr>
      </tfoot>
    </table>
  </body>
</html>
```
