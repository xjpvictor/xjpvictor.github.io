Simple editor
====

This is written in a very [simple text editor](https://simple-editor.xyz "Simple Editor").

---

Text in _italic_ **bold** <u>underline</u> <sup>superscript</sup> <sub>subscript</sub> <span style="font-family:serif;">Serif</span> and  <span style="color:red;">any inline style</span>

Define <span><dfn>terms</dfn> with definition</span>

> Quote
> 
> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Insert `inline code` or

```python
# add a code block
print('Hello world');
```

Image
----

<figure markdown="1">
<span style="display:block;margin-left:auto;margin-right:auto;max-width:auto;">
![LJIZlzHgQ7WPSh5KVTCB_Typewriter.jpg](LJIZlzHgQ7WPSh5KVTCB_Typewriter.jpg "LJIZlzHgQ7WPSh5KVTCB_Typewriter.jpg")
</span>
<figcaption markdown="1">
Photo by <a href="https://unsplash.com/@florianklauer" target="_blank" title="Author">Florian Klauer</a> on <a href="https://unsplash.com/photos/mk7D-4UCfmg" target="_blank" title="Unsplash">Unsplash</a>
</figcaption>
</figure>

TEX
----

It also supports Mathjax with mhchem.

Inline equation \\( E = mc^2 \\)

Or equation block

\\[ \lambda = \frac{c}{\nu} \\]

Chemical equations

\\[ \ce{Hg^2+ ->[I-] HgI2 ->[I-] [Hg^{II}I4]^2-} \\]

<script type="text/javascript" crossorigin="anonymous" src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script>
  //var polyfillscript = document.createElement('script');
  //polyfillscript.type = 'text/javascript';
  //polyfillscript.src = 'https://polyfill.io/v3/polyfill.min.js?features=es6';
  //polyfillscript.crossOrigin = 'anonymous';
  //document.body.appendChild(polyfillscript);
  MathJax = {
    loader: {
      load: ['[tex]/autoload']
    },
    tex: {
      packages: {
        '[+]': ['autoload']
      },
      inlineMath: [['\\(', '\\)']]
    },
    svg: {
      fontCache: 'global'
    },
    chtml: {
      scale: 1.0,
      minScale: .5,
      mtextFont: '',
      unknownFamily: 'serif',
      mathmlSpacing: false,
      exFactor: .5
    }
  };
  //var mathjaxscript = document.createElement('script');
  //mathjaxscript.type = 'text/javascript';
  //mathjaxscript.id = 'MathJax-script';
  //mathjaxscript.async = true;
  //mathjaxscript.src = 'https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml-full.js';
  //mathjaxscript.crossOrigin = 'anonymous';
  //document.body.appendChild(mathjaxscript);
</script>
<script type="text/javascript" id="MathJax-script" async crossorigin="anonymous" src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml-full.js"></script>
