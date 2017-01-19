# RWD-fb-plugin

Workaround for Responsive width Facebook Page Plugin
  
## Restrictions

  * Using CSS3 transform [Can I use?](http://caniuse.com/#search=transform)
  * Set data-adapt-container-width="false". (or something went wrong under 500px)
  * This fb-plugin was set to 500 x 500. [See more on FB page-plugin](https://developers.facebook.com/docs/plugins/page-plugin)

## Get Started

```html
<script src="jquery.rwd-fb-plugin.js"></script>

<!--FB-page-plugin part1-->
<div id="fb-root"></div> <script>(function(d, s, id) { ... } </script>

<!--FB-page-plugin part2-->
<div class="fb-page"> ... </div>

$(function(){
    $('.fb-page').rwd();
});
```

## Demo

[Demo](http://kuofp.github.io/RWD-fb-plugin/)