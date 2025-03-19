---
layout: about
title: about
permalink: /
subtitle: # maybe write phd student at .. info here. <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc. 

profile:
  align: right
  image: #prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: #> 
  # <p>PhD Student at Berlin School of Economics</p> 
  # <p>555 your office number</p>
  # <p>123 your address street</p>
  # <p>Your City, State 12345</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Welcome! I am a Econ PhD student at the [Berlin School of Economics](https://berlinschoolofeconomics.de/home). I also work as a research associate at the [German Institute of Economic Research](https://www.diw.de/sixcms/detail.php?id=diw_01.c.617916.en) (DIW Berlin).

My research interests include labor economics, applied microeconomics and structural microeconometrics.

You can reach me via [email](mailto:maxischaller@diw.de).

Please find my CV <a href = "../assets/pdf/cv-schaller.pdf">here</a>.

<hr>

<div class="publications">
    <h2>Publications</h2>
    {% bibliography -f papers.bib %}
</div>
