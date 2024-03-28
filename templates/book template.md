<%*
let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Title");}await tp.file.rename(title)-%>---type: bookaliases: - "& <%* tR += title %>"cover: {{coverUrl}}start:end:status: todorecommendedby:---___tags:: prev:: [[books|назад в библиотеку]]category::author:: [[{{author}}]]children::___PDF![cover|150]({{coverUrl}})___<% tp.file.cursor(0) %>
