(Firefox vs Chrome/Safari)

Input (with 1 nesting level available):
```
<table>
  <tr>
    <td>
```

Firefox:
```
<table></table>
<tbody></tbody>
<tr></tr>
<td></td>
```

Chrome:
```
<table></table>
<tbody>
  <tr></tr>
  <td></td>
</tbody>
```

Safari (needs test case change, see comment in the code):
```
<table></table>
<tbody>
  <tr></tr>
  <td></td>
</tbody>
```