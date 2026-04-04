---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
- **Ph.D. in Biosystems Engineering & Soil Science**, University of Tennessee, Knoxville  
- **M.S. in Agricultural Engineering**, Chungnam National University, South Korea  
- **B.S. in Agricultural Engineering**, Hajee Mohammad Danesh Science and Technology University  

---

## Professional Experience
- **Postdoctoral Research Associate**  
  Texas A&M AgriLife Research, College Station, TX  
  *Group of AI in Agriculture (GAIA)*  

- **Graduate Research Assistant**  
  University of Tennessee, Knoxville  

- **Research Assistant**  
  Chungnam National University, South Korea  

---

## Research Expertise
- Artificial Intelligence in Agriculture  
- Computer Vision for Livestock Monitoring  
- Precision Livestock Farming  
- Machine Learning & Deep Learning  
- Geospatial Data Analysis (GPS, NDVI)  
- Multimodal Data Integration  

---

## Technical Skills
- **Programming:** Python, MATLAB  
- **AI/ML:** PyTorch, TensorFlow, Scikit-learn  
- **Computer Vision:** OpenCV, YOLO, Image Processing  
- **Geospatial:** QGIS, ArcGIS, Raster & GPS Analysis  
- **Data Analysis:** Pandas, NumPy, Data Visualization  

---

## Publications
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

## Conference Presentations
<ul>
{% for post in site.publications reversed %}
  {% if post.category == "conferences" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}
</ul>

---

## Awards & Honors
- Outstanding Graduate Student Award, International Conference on Precision Agriculture (ICPA), 2024  

---

## Professional Activities
- Reviewer for peer-reviewed journals in agricultural engineering and AI  
- Member of professional societies in precision agriculture and biosystems engineering  
