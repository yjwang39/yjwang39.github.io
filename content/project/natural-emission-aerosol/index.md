---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CoAerM-CESM: an updated aerosol module for dust, marine aerosol emissions, and secondary organic aerosol formation"
summary: "This update improves the accuracy of aerosol simulations and highlights the impact of biological variability on emissions, enhancing the model's ability to represent complex aerosol processes and their climate effects."
authors: [admin, Peng Zhang, Jiawei Li, Zhiwei Han, Yanxu Zhang]
tags: ["Aerosol", "Emission", "CESM"]
date: 2022-10-20T13:15:40+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Aerosols play a crucial role in shaping Earth's climate, influencing radiative properties, weather patterns, and biogeochemical processes. Our research has advanced the representation of aerosols in the Community Earth System Model (CESM) by developing updated emission schemes for dust, sea-salt, and marine primary organic aerosols (MPOA). These updates improve dust aerosol optical depth simulations and shorten dust residence time, leading to more accurate concentration predictions in regions like North Africa and Central Asia. Additionally, our modifications to the sea-salt emission scheme, which account for sea surface temperature and humidity, further refine the accuracy of these emissions.
![Coupling framework](coupling.png)
We also extended the model to incorporate MPOA emissions, highlighting the substantial impact of phytoplankton diversity on aerosol formation. By coupling these emissions with the ocean's physical and biological processes, we capture a more nuanced interaction between marine ecosystems and atmospheric aerosols. This approach demonstrates the critical role biological variability plays in shaping aerosol dynamics, emphasizing the importance of integrating oceanic data in atmospheric modeling.

In addition to emission updates, we improved CESM’s chemical processes by introducing a new pathway for secondary organic aerosol (SOA) formation. This new mechanism, which includes the irreversible uptake of dicarbonyl compounds, enhances the model’s ability to simulate natural aerosol formation and distribution. Overall, these enhancements to CESM provide a more comprehensive understanding of how natural aerosols are produced and how they interact with the Earth’s climate system, paving the way for better predictions of future climate scenarios.