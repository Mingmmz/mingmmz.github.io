---
layout: about
title: About
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile: false
  # align: right
  # image: IMG_2851.JPG
  # image_circular: false # crops the image to make it circular
  # more_info: >
  #   <p>555 your office number</p>
  #   <p>123 your address street</p>
  #   <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit:  # leave blank to include all the news in the `_news` folder

# latest_posts:
#   enabled: true
#   scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#   limit: 3 # leave blank to include all the blog posts
---

<div class="profile float-right">
  {% include figure.liquid
    loading="eager"
    path="assets/img/IMG_2851.JPG"
    title="Mingzhuo Ma"
    class="img-fluid z-depth-1 rounded"
  %}

  <div class="social profile-social">
    <div class="contact-icons">
      {% social_links %}
    </div>
  </div>
</div>

I am a 1st-year CSE PhD student at University of Michigan-Ann Arbor, advised by [Prof. Ke Sun](https://samsonsjarkal.github.io/KeSun/) and [Prof. Junyi Zhu](https://www.junyizhu.com/).
My research interests lie in exploring various **sensing technologies** and creating innovative **wearables**, particularly for **healthcare** applications.


Prior to UMich, I worked in [WI Lab](https://wearableintelligencelab.github.io/group_website/index.html) led by [Prof. Yiyue Luo](https://yyueluo.com/) at University of Washington, Seattle (UW). I also worked in [Ubiquitous Computing Lab](https://ubicomplab.cs.washington.edu/), led by [Prof. Vikram Iyer](https://homes.cs.washington.edu/~vsiyer/), and [Prof. Shwetak Patel](https://www.cs.washington.edu/people/faculty/shwetak-patel/).


I received my B.S. degree in EEE jointly offered by the University of Electronic and Science Technology of 
China (UESTC) and the University of Glasgow (UoG) in 2023, minoring in Interactive New Media Art (iArt), advised by [Prof. Lina Mohjazi](https://www.gla.ac.uk/schools/engineering/staff/linamohjazi/#biography,researchinterests).

Beyond engineering, I also designed an art installation "Soft Machine", an interactive music game "Five Notes", and a Roblox maze FPS game "Find your Sister!". I attended the Chengdu Transcendental Implant Art Exhibition held by UESTC and Chongqing Times Art Museum as a young artist and interviewed by Chengdu TV in 2021.


<style>
  .news .table-responsive {
    max-height: 320px !important;
    overflow-y: auto !important;
  }
</style>

<style>
  .profile .profile-social .contact-icons {
  justify-content: center;
}

/* optional: slightly smaller icons */
.profile .profile-social .contact-icons a {
  font-size: 2rem;
}

/* News scrolling */
.news .table-responsive {
  max-height: 320px !important;
  overflow-y: auto !important;
}

/* ================================
   Capitalize homepage section titles
   ================================ */

h2 a[href$="/news/"],
h2 a[href$="/publications/"] {
  text-transform: capitalize;
}


/* ================================
   News scrolling
   ================================ */

.news .table-responsive {
  max-height: 320px !important;
  overflow-y: auto !important;
}


/* ================================
   Bold my name in publications
   ================================ */

.publications .author em,
.publications .author em a {
  font-weight: 400 !important;
  font-style: normal !important;
}


/* ================================
   Larger publication preview images
   ================================ */

@media (min-width: 576px) {
  .publications .abbr {
    flex: 0 0 250px !important;
    width: 250px !important;
    max-width: 250px !important;
  }

  .publications .abbr + .col-sm-8 {
    flex: 1 1 0 !important;
    width: auto !important;
    max-width: none !important;
  }

  .publications .abbr img.preview {
    width: 100% !important;
    max-width: 100% !important;
    height: auto !important;
    object-fit: contain;
  }
}
</style>

<!-- # Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

# Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

# Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
