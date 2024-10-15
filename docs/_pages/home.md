---
layout: splash
permalink: /
hidden: true
title: Portfolio
header:
  #overlay_color: "#5e616c"
  overlay_image: /assets/images/shrey_flower.jpeg
excerpt: 
  <br />
services:
  - excerpt: "<h1>Services</h1>"  
feature_row_services:
  - image_path: /assets/images/sen-flower.jpeg #/assets/images/sen-mountains.jpeg
    alt: ""
    title: "Next Step Data Science"
    excerpt: "learn what they don't teach in school <br> overcome imposter syndrome <br> discover mindful coding"
    url: "/next-step-data-science/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

projects:
  - title: "<h1>Projects</h1>"
feature_row_projects:
  - image_path: /assets/images/shrey_tbook.png
    alt: ""
    title: "Travel By Book"
    excerpt: "for when you want a book about a place"
    url: "https://travelbybook.streamlit.app/"
    btn_class: "btn--primary"
    btn_label: "Go To Project"
  - image_path: /assets/images/pensive_tarot.png #/assets/images/shrey_fairshare.png
    alt: ""
    title: "Pensive Tarot"
    excerpt: "reflect on your life through writing"
    url: "https://shrey.pythonanywhere.com/"
    btn_class: "btn--primary"
    btn_label: "Go To Project"
  - image_path: /assets/images/shrey_fairshare.png
    alt: ""
    title: "Fair Share Cost Calculator"
    excerpt: "for when splitting 50-50 isn't fair"
    url: "https://fairshare.streamlit.app/"
    btn_class: "btn--primary"
    btn_label: "Go To Project"  
code:
  - image_path: ""
    title: "Code Base"   
feature_row_code:
  - image_path: /assets/images/statistical_cookbook_codebase.png
    alt: ""
    title: "Statistical Cookbook"
    excerpt: "my personal storehouse of statistical knowledge"
    url: "https://github.com/ShreyanSen/statistics_cookbook"
    btn_class: "btn--primary"
    btn_label: "Go To Code" 
  - image_path: /assets/images/autojournal_codebase.png
    alt: ""
    title: "AutoJournal"
    excerpt: "get monthly AI smart summaries for your diary using local llms (don't send it to the cloud!)"
    url: "https://github.com/ShreyanSen/AutoJournal"
    btn_class: "btn--primary"
    btn_label: "Go To Code" 
  - image_path: /assets/images/yt_transcription_codebase.png
    alt: ""
    title: "YT Transcription GUI Exe"
    excerpt: "download transcripts of videos from youtube via desktop GUI run from .exe equivalent"
    url: "https://github.com/ShreyanSen/youtube_transcription_desktop_app"
    btn_class: "btn--primary"
    btn_label: "Go To Code" 
  - image_path: /assets/images/simulations_codebase.png
    alt: ""
    title: "Simulations Notebooks"
    excerpt: ""
    url: "https://github.com/ShreyanSen/simulations"
    btn_class: "btn--primary"
    btn_label: "Go To Code" 
  - image_path: /assets/images/travel_by_book_codebase.png
    alt: ""
    title: "Travel By Book Codebase"
    excerpt: ""
    url: "https://github.com/ShreyanSen/TravelByBook"
    btn_class: "btn--primary"
    btn_label: "Go To Code"
  - image_path: /assets/images/tarot_codebase.png
    alt: ""
    title: "Pensive Tarot Codebase"
    excerpt: ""
    url: "https://github.com/ShreyanSen/FairShare"
    btn_class: "btn--primary"
    btn_label: "Go To Code"
  - image_path: /assets/images/fairshare_codebase.png
    alt: ""
    title: "Fair Share Codebase"
    excerpt: ""
    url: "https://github.com/ShreyanSen/FairShare"
    btn_class: "btn--primary"
    btn_label: "Go To Code"  
  


writing:
  - image_path: /assets/images/shrey_writing.png
    alt: ""
    title: "Reflection"
    excerpt: "it's mirrors all the way down"
    url: "https://shreyansen.github.io/writing/"
    btn_class: "btn--primary"
    btn_label: "Click To Feel"
mindful:
  - image_path: /assets/images/mndfl_certificate.png
    alt: ""
    title: "Mindfulness Instruction"
    excerpt: "teaching fundamentals of mindfulness"
    url: "/mindfulness-instruction/"
    btn_class: "btn--primary"
    btn_label: "Click To Pause"
feature_row_archived:
  - image_path: /assets/images/sen-mountains.jpeg
    alt: ""
    title: "Data Scientist"
    excerpt: ""
    url: "https://www.linkedin.com/in/shreyansen/"
    btn_class: "btn--primary"
    btn_label: "Click To Think"
  - image_path: /assets/images/sen-water.jpeg
    alt: ""
    title: "Mindfulness Instructor"
    excerpt: ""
    url: "/mindfulness-instruction/"
    btn_class: "btn--primary"
    btn_label: "Click To Pause"
  - image_path: /assets/images/sen-flower.jpeg
    alt: ""
    title: "Writer"
    excerpt: ""
    url: "https://shreyansen.github.io/writing/"
    btn_class: "btn--primary"
    btn_label: "Click To Feel"  
  - image_path: /assets/images/sen-flower.jpeg
    alt: ""
    title: "Test"
    excerpt: "Just testing what this does here"
    url: "https://shreyansen.github.io/writing/"
    btn_class: "btn--primary"
    btn_label: "Click To Feel" 
---

<!---
dropped lines: 
{% include feature_row id="services" type="center" %}
{% include feature_row id="projects" type="center" %}

-->
{% include feature_row id="feature_row_projects"%}
{% include feature_row id="feature_row_code"%}
{% include feature_row id="feature_row_services" type="center"%}
{% include feature_row id="writing" type="center"%}
{% include feature_row id="mindful" type="center"%}


