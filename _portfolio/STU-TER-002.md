---
title: Studio 201
subtitle: Prachtige studio dicht bij Gasthuisberg 26m².
width: full
image: portfolio-1-thumb.jpg
topics: [studio]
navbar:
  sticky: false
  transparent: true
  transparent_color: light
header:
  layout: center # Options: center 1-2 or 2-3
  background_image: IMG_20140829_173007.jpg
  background_overlay: "rgba(0, 0, 0, 0.5)"
  color: light
  header_size: xlarge
  parallax: true
---

test

{% include block.html 
  block="content-post"
  section_size="medium"
  section_container="xsmall"
  section_header_align="center"
  section_title="The challenge"
  block_title="false"
%}

{% include gallery.html 
	grid="1-2"
	gallery="studio201"
	caption="true"
	lightbox="true"
  section_size="medium"
  section_padding_remove="top"
%}

{% include block.html 
  block="content-post2"
  section_size="medium"
  section_padding_remove="top"
  section_container="xsmall"
  section_header_align="center"
  section_title="The solution"
  block_title="false"
%}

{% include image.html 
	src="portfolio-4-header.jpg"
  alt="Some alt title"
  section_size="medium"
  section_padding_remove="top"
  section_container="small"
%}