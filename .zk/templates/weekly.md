---
title: {{date now "timestamp"}}
id: {{id}}
date: {{date}}
tags: [weekly]
---


# {{date now "timestamp"}}

{{prepend '> ' (sh 'fortune')}}

## {{format-link "(sh "'date -d'next-monday - 1week' +%Y%m%d'")" }} -- Monday
## {{format-link "(sh "'date -d'next-monday - 1week' +%Y%m%d'")" }}  -- Tuesday
## {{format-link "(sh "'date -d'next-monday - 1week' +%Y%m%d'")" }}  -- Wednesday
## {{format-link "(sh "'date -d'next-monday - 1week' +%Y%m%d'")" }}  -- Thursday
## {{format-link "(sh "'date -d'next-monday - 1week' +%Y%m%d'")" }}  -- Friday
## {{format-link "(sh "'date -d'next-monday - 1week' +%Y%m%d'")" }}  -- Saturday
## {{format-link "(sh "'date -d'next-monday - 1week' +%Y%m%d'")" }}  -- Sunday
