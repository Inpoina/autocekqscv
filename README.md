# autocekqscv

```
document.querySelectorAll('input[type="radio"]').forEach(rb => {
    rb.click();
});

```
#versi 2

```
document.querySelectorAll('input[type="radio"][value="RadioButtonOKChief"]').forEach(rb => {
    rb.click();
});

```

#versi id

```
document.querySelectorAll('input[id*="RadioButtonOKChief"]').forEach(rb => {
    rb.click();
});

```

