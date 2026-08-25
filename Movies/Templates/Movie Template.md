---
Director: '[[<% await tp.system.prompt("Director") %>]]'
tags:
  - movie
Watched:
Cover Image: "[[<% tp.file.title %>.jpg]]"
Type:
Length (min): <% tp.system.prompt("Length in min") %>
Date Added: <% tp.date.now() %>
---
![[<% tp.file.title %>.jpg]]
# Notes
