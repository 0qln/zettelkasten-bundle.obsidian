---
id: <% tp.frontmatter.id = `note-${Date.now()}` %>
aliases:
  - <% tp.frontmatter.alias = tp.file.title %>
tags:
---
<% tp.file.rename(tp.frontmatter.id) %>
# <% tp.frontmatter.alias %>

<% tp.file.cursor(0) %>


# References

