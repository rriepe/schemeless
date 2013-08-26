SchemeLESS
===

SchemeLESS is a color scheme file for [LESS](http://lesscss.org/) that enables you to easily generate color schemes and customize them as much or as little as you want.

<dl>
  <dt>Version</dt>
  <dd>1.0</dd>
</dl>


How to use it
---

Edit or overwrite the `@seed-color` value to generate a scheme based on that color.

SchemeLESS works best when it’s imported and compiled alongside other LESS files that reference it. In a pinch, just paste it in.


Example `index.less`
---

    @import "scheme.less"; // color scheme
    @import "style.less"; // your own styles
