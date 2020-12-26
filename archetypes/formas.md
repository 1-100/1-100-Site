---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
autorias: ["Nome da Pessoa"]
plataformas: ["Plataforma 1", "Plataforma 2"]
descricao: "Descricao"
autorias_url: ["https://sites.com"]
codigo: ""
url: "/formas/{{ .File.BaseFileName }}"
---