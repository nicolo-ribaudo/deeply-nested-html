(Firefox/Chrome vs Safari)

Input (with 2 nesting levels available):
```
<span>
  <span>
    <a></a>
  </span>
  <b></b>
</span>
```

Firefox:
```
<span>
  <span></span>
  <a></a>
  <b></b>
</span>
```

Chrome:
```
<span>
  <span></span>
  <a></a>
  <b></b>
</span>
```

Safari (needs test case change, see comment in the code):
```
<span>
  <span></span>
  <a></a>
</span>
<b></b>
```