# Link-Confirm 라이브러리

control jQuery's a tag

## installation

put this link on header of a HTML

jQuery cdn coded should be previous this code

```html
 <script src="https://code.jquery.com/jquery-3.7.1.js"></script>
<script scr="https://cdn.jsdelivr.net/gh/PyojaeSohnkh15/cdn/link-confirm/index.js"></script
```

## usage

use 'link-confirm' as a class in `<a>`

```html
<a href="https://www.google.com" class="link-confirm">Google</a>
```

## customize
if wanna change comment, set 'data-comment'

```html
 <a href="#" class="link-confirm" data-comment="delete?">delete</a>
```

if users set 'data-comment', get priority
