---
title: Refs and quotes
description: "Documentation for adding refs and quotes."
date: 2024-12-23T22:12:20.059Z
preview: ""
draft: true
tags: []
categories: []
---
# Guide for adding references and quotes

IF there is a ```<quote>``` element, do it first!

## quote (always) AND ref (if quote not present)
find the corresponding range,
add html address with a ```<ref xml:id="XMIrefID" source="http://ADDRESS">```

IF only ref or quote, you are done

IF both, to ref element then add <ref xml:id="XMLID" corresp="XMLID of referenced quote."
