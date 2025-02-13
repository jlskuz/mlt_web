---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.tonemap_vaapi"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: tonemap_vaapi  
media types:
Video  
description: VAAPI VPP for tone-mapping  
version: Lavfi7.110.100  
creator: libavfilter maintainers  

## Parameters

### av.format

  
description:
Output pixel format set  
type: string  
readonly: no  
required: no  

### av.matrix

  
description:
Output color matrix coefficient set  
type: string  
readonly: no  
required: no  

### av.m

  
description:
Output color matrix coefficient set  
type: string  
readonly: no  
required: no  

### av.primaries

  
description:
Output color primaries set  
type: string  
readonly: no  
required: no  

### av.p

  
description:
Output color primaries set  
type: string  
readonly: no  
required: no  

### av.transfer

  
description:
Output color transfer characteristics set  
type: string  
readonly: no  
required: no  

### av.t

  
description:
Output color transfer characteristics set  
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

