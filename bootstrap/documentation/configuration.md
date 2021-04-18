---
title: "Configuration"
date: 2021-04-18T20:29:29+07:00
---




### How to get configuration

If the global `baseof.html` is used then the configuration is loaded before any 
other activities. In any layout we can call the configuration with the following 
call:

```gotemplate
{{- $config := .Scratch.Get "config" -}}
```

`$config` will contain the configuration object.
