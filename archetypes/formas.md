---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
autorias: ["Guilherme Vieira"]
plataformas: ["Processing"]
descricao: "Descricao"
autorias_url: ["https://guilhermevieira.info"]
url: "/formas/{{ .File.BaseFileName }}"
---