---
layout: splash
permalink: /
hidden: true

header:
  overlay_color: "#0b1c2d"
  overlay_image: /assets/images/hero-mechanics.jpg
  actions:
    - label: "<i class='fas fa-search'></i> Browse Knowledge Base"
      url: "/design/"
    - label: "<i class='fas fa-book'></i> Volumes"
      url: "/volumes/"

excerpt: >
  <strong>Mechanics Knowledge Platform</strong><br>
  An academically structured engineering knowledge base covering
  <em>Mechanical Design, CAD Systems, Manufacturing, and Applied Mechanics</em>.<br>
  <small>Curated by Berkay Aktaş</small>

feature_row:
  - image_path: /assets/images/feature-design.png
    alt: "mechanical design"
    title: "Design & CAD"
    excerpt: "AutoCAD, FreeCAD, Solid modeling, parametric workflows, and industrial drawing standards."
    url: "/design/"
    btn_class: "btn--primary"
    btn_label: "Enter Design Library"

  - image_path: /assets/images/feature-volumes.png
    alt: "engineering volumes"
    title: "Engineering Volumes"
    excerpt: "Structured academic volumes covering statics, dynamics, strength of materials, kinematics, and mechanisms."
    url: "/volumes/"
    btn_class: "btn--primary"
    btn_label: "Browse Volumes"

  - image_path: /assets/images/feature-research.png
    alt: "technical research"
    title: "Technical Articles"
    excerpt: "Peer-style technical explanations, worked examples, command references, and applied problem solving."
    url: "/posts/"
    btn_class: "btn--primary"
    btn_label: "Read Articles"

feature_row2:
  - image_path: /assets/images/feature-autocad.png
    alt: "autocad"
    title: "AutoCAD"
    excerpt: "Line, polyline, constraints, layers, blocks, dimensioning, plotting, and professional drafting workflows."
    url: "/design/autocad/"
    btn_class: "btn--info"
    btn_label: "Open AutoCAD"

  - image_path: /assets/images/feature-freecad.png
    alt: "freecad"
    title: "FreeCAD"
    excerpt: "Parametric solids, assemblies, FEM, CAM, and technical drawing environments."
    url: "/design/freecad/"
    btn_class: "btn--info"
    btn_label: "Open FreeCAD"

  - image_path: /assets/images/feature-manufacturing.png
    alt: "manufacturing"
    title: "Manufacturing"
    excerpt: "Machining, tolerancing, surface quality, metrology, and production engineering principles."
    url: "/manufacturing/"
    btn_class: "btn--info"
    btn_label: "Explore Manufacturing"
---
{% include feature_row %}
{% include feature_row2 %}
