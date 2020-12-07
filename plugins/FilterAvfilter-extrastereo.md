---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.extrastereo"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: extrastereo  
media types:
Audio  
description: Increase difference between stereo audio channels.  
version: Lavfi7.85.100  
creator: libavfilter maintainers  

## Parameters

### av.m

  
description:
set the difference coefficient  
type: float  
readonly: no  
required: no  
minimum: -10  
maximum: 10  
default: 2.5  

### av.c

  
description:
enable clipping  
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

