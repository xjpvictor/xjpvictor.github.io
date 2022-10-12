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

    # add a code block
    print('Hello world');

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

Inline equation $$ E = mc^2 $$

Or equation block

\\[ \lambda = \frac{c}{\nu} \\]

Chemical equations

\\[ \ce{Hg^2+ ->[I-] HgI2 ->[I-] [Hg^{II}I4]^2-} \\]

<script type="text/javascript" async src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML"> </script>
<script>
MathJax.Hub.Config({
    TeX: {
      equationNumbers: {
        autoNumber: "AMS"
      }
    },
    tex2jax: {
    inlineMath: [ ['$', '$'] ],
    displayMath: [ ['\[', '\]'] ],
    processEscapes: true,
  }
});
</script>
