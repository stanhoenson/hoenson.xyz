---
title: "{{ replace .Name "-" " " | title | humanize }}"
date: {{ dateFormat "2006-01-01" .Date }}
draft: false
---

