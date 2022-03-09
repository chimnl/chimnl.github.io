---
layout: default
title: "CHI MNL | CHI MNL Series 01: Why we teach and do research in HCI"
speakers: [ { name: "Briane Paul V. Samson", title: "Associate Professor, DLSU", image: "../../assets/img/execom/briane.jpg" }, { name: "Toni-Jan K Monserrat", title: "Assistant Professor, UPLB", image: "../../assets/img/execom/tj.png" }, { name: "Jordan Aiko Deja", title: "PhD Student, UP FAMNIT", image: "../../assets/img/execom/jordan.jpg" }, { name: "Ralph Vincent Regalado", title: "CEO, Senti AI", image: "../../assets/img/execom/ralph.jpg" } ]
---
<style>
    section{
        padding: 96px 0;
    }
</style>
<section>
    <div class="container">
        <h1>CHI MNL Series 01: Why we teach and do research in HCI</h1>
        <h4 class = "mb-4">March 17, 2022 (Tuesday), 6pm PH Time via Zoom</h4>
        <p>Research in Human Computer Interaction (HCI) has always brought the most innovative technologies - from the first mouse, to the GUI all the way to user gestures and mixed reality. CHI MNL believes that the best way to foster such potential is to begin nurturing from the roots - teaching HCI in the university and preparing early career HCI researchers. Learn more from the execom of CHI MNL in this FREE event. Please register in the link provided.</p>
        <h4>Speakers: </h4>
        <div class = "d-flex flex-wrap justify-content-center my-5">
        <!-- {% assign members = site.data.execom.committee %} -->
            {% for speaker in page.speakers %}
                <div class = "user shadow bg-white rounded m-3 text-center">
                    <div class="user-img bg-secondary mx-auto" style="background: url( {{ speaker.image }} ); background-position: center; background-size: cover;"></div>
                    <p class = "text-center mt-2 m-0 member-name text">{{ speaker.name }}</p>
                    <p class ="m-0 text-center">{{ speaker.title }}</p>
                </div>
            {% endfor %}
        </div>
        <h4>How do I Participate: </h4>
        <p>The event is free however prior registration is required. Please register in the link to be able to get the meeting details.</p>
        <a href="https://zoom.us/j/92085470159?pwd=QUlmS3FJTWJRcy8zSFc3VWZuVzV3Zz09" class="btn btn-primary" target="_blank" > Register here </a>
    </div>
</section>