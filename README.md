# beforeunload-test

Show confirm dialog on `beforeunload`.

```js
window.addEventListener("beforeunload", (ev) => {
  // Spec compliant way, for all browser
  ev.preventDefault();
  // Only for Chrome
  ev.returnValue = "";
});
```
