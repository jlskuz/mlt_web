---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.aeval"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: aeval  
media types:
Audio  
description: Filter audio signal according to a specified expression.  
version: Lavfi7.57.100  
creator: libavfilter maintainers  

## Parameters

### av.exprs

  
description:
set the &#39;|&#39;-separated list of channels expressions  
type: string  
readonly: no  
required: no  

### av.channel_layout

  
description:
set channel layout  
type: string  
readonly: no  
required: no  

### av.c

  
description:
set channel layout  
type: string  
readonly: no  
required: no  

### position

  
description:
The MLT position value to set on avfilter frames  
type: string  
readonly: no  
required: no  
default: frame  
values:  

* frame
* filter
* source
* producer

