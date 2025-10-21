(all match)

Input (with 2 nesting level available):
```
<table>
  <tbody>
    <tr>
      <td>
```

Firefox:
```
<table>
  <tbody></tbody>
  <tr></tr>
  <td></td>
</table>
```

Chrome:
```
<table>
  <tbody></tbody>
  <tr></tr>
  <td></td>
</table>
```

Safari (needs test case change, see comment in the code):
```
<table>
  <tbody></tbody>
  <tr></tr>
  <td></td>
</table>
```