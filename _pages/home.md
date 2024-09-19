---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/base/intro-01.png
  overlay_filter: 0.25 # same as adding a set level of opacity to a black background
  actions:
    - label: "About"
      url: "/about/"
excerpt: >
  A consortium of academic institutions in Slovenia that integrates the country's research infrastructure focusing on structural biology
feature_row:
  - image_path: /assets/images/base/instruct-eric-button.png
    alt: "Instruct-ERIC"
    title: "Instruct-ERIC"
    excerpt: "What [Instrust-ERIC](https://instruct-eric.org/) is about, and what it offers to researchers from member countries."
    url: "instruct-eric"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/base/how-to-apply-button.png
    alt: "application"
    title: "How to apply"
    excerpt: "How to apply for funded access to the services offered by [Instruct-ERIC](https://instruct-eric.org/)."
    url: "/application/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/base/infrastructure-slovenia-button.png
    alt: "infrastructure"
    title: "Infrastructure"
    excerpt: "Info on structural biology infrastructure available in Slovenia."
    url: "/infrastructure/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
gallery:
  - url: https://www.ki.si/
    image_path: /assets/images/logo/ki-logo-en-tsp-bd-1200x500.png
    alt: "National Institute of Chemistry"
    title: "National Institute of Chemistry"
  - url: https://www.uni-lj.si/
    image_path: /assets/images/logo/ul-logo-en-tsp-bd-1200x500.png
    alt: "University of Ljubljana"
    title: "University of Ljubljana"
  - url: https://www.ijs.si/
    image_path: /assets/images/logo/ijs-logo-en-tsp-bd-1200x500.png
    alt: "Jožef Stefan Institute"
    title: "Jožef Stefan Institute"
  - url: https://cipkebip.org/
    image_path: /assets/images/logo/cipkebip-logo-en-tsp-bd-1200x500.png
    alt: "Centre of Excellence for Integrated Approaches in Chemistry and Biology of Proteins"
    title: "Centre of Excellence for Integrated Approaches in Chemistry and Biology of Proteins"
  - url: https://www.nib.si/
    image_path: /assets/images/logo/nib-logo-slen-tsp-bd-1200x500.png
    alt: "National Institute of Biology"
    title: "National Institute of Biology"
  - url: https://www.ung.si/
    image_path: /assets/images/logo/ung-logo-sl-tsp-bd-1200x500.png
    alt: "University of Nova Gorica"
    title: "University of Nova Gorica"
  - url: https://www.um.si/
    image_path: /assets/images/logo/um-logo-en-tsp-bd-1200x500.png
    alt: "University of Maribor"
    title: "University of Maribor"
---

**Info Notice:** Instruct.SI is organizing a three-day workshop [**Basics of Methodological Approaches in Structural Biology**](/bmasb2024/), aimed at students and researchers who would like to obtain or refresh basic knowledge on high-resolution structural biology approaches: macromolecular crystallography (MX), nuclear magnetic resonance (NMR), and cryogenic electron microscopy (cryo-EM). Date: 5–7 November 2024.
{: .notice--info}

{% include feature_row %}

## Recent posts

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

<div class="entries-{{ entries_layout }}">
  {% for post in posts limit:3 %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

[More posts](/year-archive/){: .btn .btn--info}

## Member institutions

{% include gallery %}

---

[Impressum](/impressum/)