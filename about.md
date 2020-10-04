---
title: About
date: 2018-09-25 08:37:54 +0000
layout: test
---


We created Cut to make better use of the web-based technologies and people’s growing online presence in our research. We wanted to deal with three issues. 

<br />
First, we were looking to go beyond simple multiple choice questions and scales in our studies. Psychologists have developed sophisticated methods to measure specific psychological phenomena. However, these tools are often not up to date; they are platform dependent, they use software patterns that make them hard to maintain, their code is written in obsolete programming languages, their interface is reminiscent of Windows 95 and Netscape Navigator, and so forth. If we wanted to use these research instruments, we had to implement our own version of them from scratch.

<br />
A second issues was being able to run these instruments on mobile phones. People today use their phones more than their computers. Moreover, using a computer, unless for work or watching stuff on a bigger screen, is almost a bizarre activity these days. Majority of non-work stuff such as social media use, reading the news, game-play, shopping, etc happens on smartphones or tablets. And these are amazing tools with awesome capabilities, they are portable and they are everywhere, with people relying on them for every little thing. This means we can access a much larger population, in arguably more ecologically valid settings, at significantly lower costs. We do not want to lose out on this opportunity and so we need to do better than sending out a URL to surveys.

<br />

Finally, when teaching psychology to undergraduates, we noticed that our methods and tools can be discouragingly old for young students. It’s 2018 and almost every freshman has lived their entire life with access to  internet and smartphones. They learn better by seeing and doing things in the medium they are familiar with, rather than reading or having someone explain things to them. Furthermore, having to learn about multiple platforms sometimes prevents students from carrying out actual research projects. As a remedy, we further developed Cut to serve as a one-stop service where anyone can design simple studies, recruit participants, collect data, and see their results. With this feature, students from different backgrounds were able to to conduct their own studies, which gave them a chance to think about research ideas rather than getting stuck in their first steps.
We’ll talk about each of these in detail in other posts. For now, we are happy to have Cut openly available for test runs. We are also interested in collaborations. If you have cool tasks or research instruments that you think can be developed on Cut let us know. We’d love to hear for ya’ll.

Cheers
<br>
S. & M.

<hr class="divider" />


<div class="page-heading">Who We Are</div>
<br />
<section class="post-content">
  <div style="display: flex">
    {% for member in site.members %}
    <div class="footer-col">
      <h3 class="member-title">
        <strong>{{ member.title }}</strong>
      </h3>
      <div class="member-container">
        {{ member.content }}
      </div>
    </div>
    {% endfor %}
  </div>
</section>

<div class="about-us-image-container">
  <img src="{{ "/assets/img/s-m.jpg" | absolute_url }}" alt="Salar & Morty" class="about-us">
</div>
