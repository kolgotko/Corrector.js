# Corrector.js
For the correctness of the user input
## How to use:

```html
<input id="my-input-phone" type="text" placeholder="+7 (XXX) XXX-XX-XX" />
<input id="my-input-date" type="text" placeholder="XX.XX.XXXX" />

<script>

  var inputPhone = document.getElementById('my-input-phone');
  var inputDate = document.getElementById('my-input-date');

  var correctorPhone = new Corrector(inputPhone);
  var correctorDate = new Corrector(inputDate);

</script>
```
Enjoy ;)
