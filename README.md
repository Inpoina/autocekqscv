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

#klik 1
```
document.querySelector('a[href="../storeactivity/input_sa.aspx"]').click();

```



#klik 2

```
javascript:(async function(){var ddlShift=document.getElementById("MainContent_DDShift");if(ddlShift){ddlShift.value="Shift 1";ddlShift.dispatchEvent(new Event("change",{bubbles:true}));}await new
Promise(r=>setTimeout(r,500));var ddlStore=document.getElementById("MainContent_DDStoreActivity");if(ddlStore&&ddlStore.options.length>1){ddlStore.selectedIndex=1;ddlStore.dispatchEvent(new Event("change",{bubbles:true}));}})();
```



