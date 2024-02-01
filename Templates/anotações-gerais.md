---
Date: <% tp.date.now("DD-MM-YYYY") %>
Type: template
Theme:
Summary: ""
---
#  [[ <% tp.file.title %> ]]
<% await tp.file.move("/Anotações Gerais/" + tp.file.title)%>