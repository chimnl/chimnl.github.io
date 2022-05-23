---
layout: default
title: "CHI MNL | CHI MNL Series 04: Civic Tech in Asia"
speakers:
  [
    {
      name: "Weiyu Zhang",
      title: "National University of Singapore ",
    }
  ]
---

<style>
    section{
        padding: 96px 0;
    }
</style>
<section>
    <div class="container">
        <h1>CHI MNL Series 03: Civic Technology in Asia</h1>
        <h4 class = "mb-4">May 24, 2022 (Tuesday), 6pm PH Time via Zoom</h4>
        <p>Human Computer Interaction (HCI) is a relatively-new course recently-added to the computing programs here in the Philippines. With the covid-19 pandemic, it is more important than ever to share best practices, and equip teachers with proper tools on how to teach this exciting course. This panel is FREE and open to HCI teachers, grad students and like-minded folks. Please register in the link provided.</p>
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
        <a href="https://zoom.us/j/92971935139?pwd=b2RSMDl0TVIvbjU0NHgzSFFvQWVxQT09" class="btn btn-primary" target="_blank" > Register here </a>
    </div>
</section>
