---
title: Advantages of MNPRX Indie/Studio
layout: maya-gray
excerpt: "Advantages of MNPRX Indie/Studio"
search: false
sitemap: false
---
<!-- TwentyTwenty CSS -->
<link rel="stylesheet" href="/assets/css/plugins/twentytwenty.css" type="text/css" media="screen" />

<div class="simple-feed">
<h1> New April 2021 release! </h1>
<h3> Update and start using the latest tools </h3>
<h4> Purchase an Indie/Studio commercial license or support us on Patreon to use all tools and render at ANY resolution!</h4>
<div class="upgrade-img" style="width:80%; margin:0 auto 2rem">
  <img src="/images/patreon/Artineering-Patreon.png"/>
</div>
<hr style="height:3px; border: none; background-color:#444; color:#444">
</div>

<div class="upgrade-text-nc" markdown="1">  
Features you are missing out!

<div class="upgrade-background" markdown="1">
Anti-aliasing - improved quality
  <figure>
    <div id="comparison" style="margin: 0 auto">
       <!-- The before image is first -->
       <img src="/images/MNPRX/comparison/no-AA.png" class="pull-center"/>
       <!-- The after image is last -->
       <img src="/images/MNPRX/comparison/TAA.png" class="pull-center"/>
    </div>
  </figure>
</div>

<i class="fal fa-chevron-double-down fa-2x"></i>

<div class="upgrade-background" markdown="1">
No resolution restrictions  
  <div class="upgrade-img">
    <img src="/images/MNPRX/comparison/resolutions.svg"/>
  </div>
</div>

<i class="fal fa-chevron-double-down fa-2x"></i>

<div class="upgrade-background" markdown="1">
Bulk attribute - change multiple attributes simultaneously  
  <div class="upgrade-img">
    <img src="/images/MNPRX/bulkAttribute.png"/>
  </div>
</div>

</div>

<footer id="footer" class="site-footer">
  <p> And more... </p>
  <h3 class="top-05"> Stay in touch! </h3>
  {%- if site.footer_links -%}
    <div class="social-icons">
      {%- for footer_link in site.footer_links -%}
        {%- if footer_link.url contains "://" -%}
          {%- assign url = footer_link.url -%}
        {%- else -%}
          {%- assign url = footer_link.url | relative_url -%}
        {%- endif -%}
        <a class="social-icon" href="{{ url }}"><i class="{{ footer_link.icon | default: 'fas fa-link' }} fa-2x" title="{{ footer_link.title }}"></i></a>
      {%- endfor -%}
    </div>
  {%- endif -%}
</footer>


<!-- jquery -->
<script src="https://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>

<!-- TwentyTwenty -->
<script src="/assets/js/plugins/jquery.event.move.js" type="text/javascript"></script>
<script src="/assets/js/plugins/jquery.twentytwenty.js" type="text/javascript"></script>

<!-- Font Awesome -->
<script src="https://pro.fontawesome.com/releases/v5.7.2/js/all.js" integrity="sha384-I3Hhe9TkmlsxzooTtbRzdeLbmkFQE9DVzX/19uTZfHk1zn/uWUyk+a+GyrHyseSq" crossorigin="anonymous"></script>

<script>
$(function(){
  $("#comparison").twentytwenty({
    move_slider_on_hover: true, // Move slider on mouse hover
    no_overlay: true, //Do not show the overlay with before and after
  });
});

(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

// GDPR compliant google analytics
ga('create', '{{ site.google_analytics_flair_demo }}', {
  'storage': 'none',
  'anonymizeIp': true,
  'storeGac': false
});
ga('send', 'pageview');
</script>
