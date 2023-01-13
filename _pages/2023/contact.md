---
title: "Contact"
permalink: /2023/contact/
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/banner3.jpg
---

<style>.athere:before {content: '@'; }</style>
<script type="text/javascript">
function init(){
    var x = document.getElementsByClassName('contactaddr');
    for (var i = 0; i < x.length; i++){
        var sp = x[i];
        var mt = sp.innerHTML;
        mt = mt.replace(/<span.*\/span>/, '@');
        sp.innerHTML = '<a href="mailto:' + mt + '">' + mt + '</a>';
    }
}
window.addEventListener("load", init, false);
</script>

We will update the contact information shortly.

For questions and comments regarding the workshop please contact the organisers at <span class="contactaddr">wassa2022<span class="athere"></span>googlegroups.com</span>.

For anything regarding the **shared task**, instead use, at <span class="contactaddr">wassa2022empathy<span class="athere"></span>@gmail.com</span>.
