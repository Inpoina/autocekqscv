# autocekqscv

```
document.querySelectorAll('input[type="radio"]').forEach(rb => {
    rb.click();
});

```
#versi 2

```
document.querySelectorAll('input[type="radio"][value="RadioButtonOK"]').forEach(rb => {
    rb.click();
});

```

#versi id

```
document.querySelectorAll('input[id*="RadioButtonOK"]').forEach(rb => {
    rb.click();
});

```

