---
title: "{{ replace (replace .Name "-" " ") (now.Format "2006 01 02 ") "" }}"
author: Martyna Kościukiewicz
date: {{ .Date }}
lastmod: {{ .Date }}
type: posts
description: "Text-description"
url: /category/postname
cover:
  relative: true
  image: images/cover.png
  alt: "Some-text"
categories:
  - ML
tags:
  - tag
draft: true
---
