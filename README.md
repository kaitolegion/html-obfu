# HTML obfuscat0r

Pr0tect your html code by renaming HTML, JS, and CSS classes to randomized, making it difficult for others to reverse-engineer or steal your work.

- Normal HTML file :
```html
<div class="card w-50">
  <div class="card-body">Kaito Coding</div>
</div>
```

- Obfuscated HTML file :
```html
<div class="gywdan tgmfkg">
  <div class=emasfm>Kaito Coding</div>
</div>
```

###  Installation & Usage 

```sh
# installation
git clone https://github.com/kaitolegion/html-obfu; cd html-obfu
# usage
python3 obfu.py --htmlpath="project/*.html" --csspath="project/*.css" --jspath="project/*.js"
```
