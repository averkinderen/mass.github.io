---
title: Frequently Asked Questions
subtitle: Got questions? See the answers to the most asked questions or get in touch.
width: full
navbar:
  sticky: false
  scroll_up: true
  animation: true
  transparent: true
  transparent_color: light
header:
  layout: center # Options: left, center, 1-1, 1-2, 1-3 or 2-3
  background_image: header-4.jpg
  background_overlay: "rgba(0, 0, 0, 0.45)"
  background_align: top-center
  color: light
  header_size: xlarge
  heading_size: medium
  parallax: true
---

{% include faqs.html 
  multiple="true" 
  category="presale" 
  section_title="Veelgestelde vragen" 
  section_size="large"
  section_background="default"
  section_container="xsmall"
  section_header_align="center"
%}

{% include faqs.html 
  multiple="false" 
  category="product" 
  section_title="Juumo Vragen" 
  section_size="large"
  section_background="default"
  section_padding_remove="top"
  section_container="xsmall"
  section_header_align="center"
%}

{% include block.html 
  block="contact-button" 
  layout="1-1"
  section_size="large"
  section_background="muted"
  section_container="xsmall"
  section_content_align="center"
%}