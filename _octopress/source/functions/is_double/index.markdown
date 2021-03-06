---
layout: page
title: "JavaScript is_double function"
comments: true
sharing: true
footer: true
alias:
- /functions/view/is_double:440
- /functions/view/is_double
- /functions/view/440
- /functions/is_double:440
- /functions/440
---
<!-- Generated by Rakefile:build -->
A JavaScript equivalent of PHP's is_double

{% codeblock var/is_double.js lang:js https://raw.github.com/kvz/phpjs/master/functions/var/is_double.js raw on github %}
function is_double(mixed_var) {
  //  discuss at: http://phpjs.org/functions/is_double/
  // original by: Paulo Freitas
  //  depends on: is_float
  //        note: 1.0 is simplified to 1 before it can be accessed by the function, this makes
  //        note: it different from the PHP implementation. We can't fix this unfortunately.
  //   example 1: is_double(186.31);
  //   returns 1: true

  return this.is_float(mixed_var);
}
{% endcodeblock %}

 - [Raw function on GitHub](https://github.com/kvz/phpjs/blob/master/functions/var/is_double.js)

Please note that php.js uses JavaScript objects as substitutes for PHP arrays, they are 
the closest match to this hashtable-like data structure. 

Please also note that php.js offers community built functions and goes by the 
[McDonald's Theory](https://medium.com/what-i-learned-building/9216e1c9da7d). We'll put online 
functions that are far from perfect, in the hopes to spark better contributions. 
Do you have one? Then please just: 

 - [Edit on GitHub](https://github.com/kvz/phpjs/edit/master/functions/var/is_double.js)


### Other PHP functions in the var extension
{% render_partial _includes/custom/var.html %}
