---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
tags:
- tag1
- tag2
categories:
- cat1
- cat2
draft: true
---

{{< bundle-image name="picture.jpg" alt="Description for screen readers." caption="Some caption"  >}}
