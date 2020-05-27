---
layout: default
title: "CHI MNL"
---
<style>
    .about{
        font-size: 20px !important;
    }

</style>

<div class = "bg-primary pb-5 pt-5" style = "height:400px; ">
    <h1 class = "text-white text-center font-weight-bolder mt-5"> Manila ACM <br> SIGCHI Chapter </h1>
</div>

<section class = "pt-5 mb-5">
    <div class = "container">
        <h3 class = "font-weight-bolder" >About CHI MNL</h3>
        <p class = "about mt-5"> {{ site.data.info.about.description }} </p>
    </div>
</section>

<section  class = "pt-5 pb-5 bg-light">
    <div class = "container">
        <h3 class = "font-weight-bolder" >Upcoming Events</h3>
        {% include upcoming-events.html %}
    </div>
</section>