---
title: "RENALMRI.org"
layout: splash
permalink: /
date: 2020-04-09T12:00:00-04:00

header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/header_parenchima.png

intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

feature_row:
  - image_path: assets/images/authors/alexandra-ljimani.jpeg
    image_caption: "[DR. ALEXANDRA LJIMANI](https://unsplash.com/)"
    alt: "DR. ALEXANDRA LJIMANI"
  - image_path: assets/images/authors/pim-pullens.jpeg
    alt: "DR. IR. PIM PULLENS"
    image_caption: "[DR. IR. PIM PULLENS](https://unsplash.com/)"
  - image_path: /assets/images/authors/anna-caroli.jpeg
    alt: "DR. ANNA CAROLI"
    image_caption: "[DR. ANNA CAROLI](https://unsplash.com/)"
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - title: "Participants"
    url: /participants/
    btn_label: "Show"
    btn_class: "btn--primary"
contribution_button:
  - title: "Contribution"
    url: /contribution/
    btn_label: "How can I change something?"
    btn_class: "btn--primary"
meeting_button:
  - title: "5th international renal imaging meeting"
    url: /contribution/
    btn_label: "11/12 Sept 2023 - 5th international renal imaging meeting"
    btn_class: "btn--primary"
---

{% include feature_row id="meeting_button" type="center" %}

{% capture notice-text %}

**Coordinating research on renal MRI biomarkers for clinical practice, drug development and basic research.**
The rising prevalence of Chronic Kidney Disease (CKD) poses a major public health challenge affecting >10% of the population. There exists an urgent need for better biomarkers to identify patients that are at risk of progression, or are likely to respond to (candidate) therapeutics. Magnetic Resonance Imaging (MRI) biomarkers can help to fill this gap, as they are uniquely able to track disease progression and treatment effects in the tissue itself and in a non-invasive manner. See [here](https://academic.oup.com/ndt/article/33/suppl_2/ii4/5078407?login=false) for a position statement by leading scientists and clinicians.
{% endcapture %}

{% include feature_row id="contribution_button" type="center" %}


<div class="notice--info" align="justify">
  <h1 align="center">MAGNETIC RESONANCE IMAGING
BIOMARKERS FOR KIDNEY DISEASE</h1>
  {{ notice-text | markdownify }}
</div>

{% capture mrs-workshop-text %}
In recent years, the clinical interest in renal MRI has accelerated research and development and led to a growing excitement within an emerging multidisciplinary community of nephrologists, radiologists, surgeons, radiographers, physicists, computer scientists, pathologists and physiologists. Bi-annual international meetings have been held since 2015, and national and international consortia have been funded to work on standardization of methods, preclinical research and multi-centre clinical trials. The field has seen an increasing participation from charities and the private sector, including SME's, pharmaceutical industry and MRI scanner manufacturers.

**RENALMRI.org provides a central point of access to the renal MRI community and joins up all stakeholders with an aim to speed up translation into clinical practice, drug development and basic research.**
{% endcapture %}


<div class="notice--success" align="justify">
  <h1 align="center">MISSION</h1>
  {{ mrs-workshop-text | markdownify }}
</div>

{% capture mrs-workshop-text %}
RENALMRI.org is a bottom-up member-led network coordinated by a governing committee consisting of a chair, past chair and vice chair. See [here](https://renalmri.org/governance/) for more detail.

Membership is open - if you want to join the network please contact the chair. The current RENALMRI.org governing committee consists of the following members:
- [Alexandra Ljimani](mailto:alexandra_ljimani@yahoo.de) (Chair)
- [Pim Pullens](mailto:Pim.Pullens@uzgent.be) (vice chair)
- [Anna Caroli](mailto:acaroli@marionegri.it) (past chair)
{% endcapture %}


<div class="notice--success" align="justify">
  <h1 align="center">GOVERNANCE</h1>
  {{ mrs-workshop-text | markdownify }}
</div>


{% include feature_row %}


{% capture mrs-workshop-text %}
RENALMRI.org aims to be the go-to place for information on renal imaging, but keeping this content up to date in a rapidly changing field is a challenging task. To manage this, we are forming an editorial committee whose members take ownership of a small part of the website and commit to keeping the content and format up to date. 

We are currently looking for editors in the roles below. if you are interested in one of these roles, please contact the chair [Alexandra Ljimani](mailto:alexandra_ljimani@yahoo.de):

- *Communities editor*: your role will be to ensure that all relevant international communities are represented on the [communities page](https://renalmri.org/community/). You will work with the relevant communities to identify a contact person who will provide the content for the page and keep it up to date. You will remove non-response or non-active communities from the page.
- *Resources editor*: your role will be to ensure that all resources that are relevant to the community are represented on the [resources page](https://renalmri.org/resources/). You will actively research the literature, conference proceedings and other sources that can be listed on the page, and remove resources that are no longer up to date or relevant. You will work with the editors of the individual resources (see below) to ensure consistency between the pages and avoid overlapping content.
  - *Clinical studies editor*: you will ensure the information on ongoing and past clinical studies on renal MRI is up to date and complete ([clinical studies page](https://renalmri.org/resources/studies/)). This will include making sure that all relevant clinical studies are listed, communicating with PI's to keep the listings up to date, adding links to protocol papers and publications, etc.
  - *Software editor*: you will ensure that all relevant software packages are listed in the [software resource page](https://renalmri.org/resources/software/) and work with developers to ensure the content remains up to date.
  - *Publications editor*: you will ensure listings of [published books](https://renalmri.org/resources/books/), [review papers](https://renalmri.org/resources/reviews/), [presentations](https://renalmri.org/resources/presentations/), [special issues](https://renalmri.org/resources/issues/) are complete and up to date.
- *Members editor*: the current [list of participants](https://renalmri.org/participants/) lists the names of individuals participating in the precursor project PARENCHIMA. This needs to be updated to include only those with an interest to stay in touch with the new RENALMRI.org, and will need to be extended with user profiles and contact information. Your role is to develop a format for setting up profiles, contacting individuals to enter their details and removing unresponsive members.
- *News editor*: your role will be to collect news items from all other parts of the website and the community, put those forward for inclusion in the quarterly newsletter and also send these out via social media channels such as the twitter feed @renalmri (currently a bot).

 
All editors will also be required to attend a quarterly editorial meeting with the governing committee to discuss priorities for the next quarter and identify content for the quarterly newsletter. 

{% endcapture %}


<div class="notice--success" align="justify">
  <h1 align="center">EDITORIAL COMMITTEE</h1>
  {{ mrs-workshop-text | markdownify }}
</div>


{% include feature_row id="feature_row4" type="center" %}
<!-- {% include feature_row id="intro" type="center" %} -->
