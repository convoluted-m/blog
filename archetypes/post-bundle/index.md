---
title: "{{ replace (replace .Name "-" " ") (now.Format "2006 01 02 ") "" }}"
author: Martyna Kościukiewicz
date: {{ .Date }}
lastmod: {{ .Date }}
type: posts
description: "Short description for listings/SEO"
series:
  - Example Series
cover:
  relative: true
  image: images/cover.png
  alt: "Some-text"
categories:
  - Convoluted Unraveled
tags:
  - topic-one
  - topic-two
draft: true
---
