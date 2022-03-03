---
title: {{date now "timestamp"}}
id: {{id}}
date: {{date}}
tags: [daily]
---


# {{title}}

{{sh 'curl http://wttr.in/?0'}}
{{prepend '> ' (sh 'fortune')}}
