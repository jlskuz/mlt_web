---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.realtime"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: realtime  
media types:
Video  
description: Slow down filtering to match realtime.  
version: Lavfi7.85.100  
creator: libavfilter maintainers  

## Parameters

### av.limit

  
description:
sleep time limit  
type: string  
readonly: no  
required: no  

### av.speed

  
description:
speed factor  
type: float  
readonly: no  
required: no  
default: 1  
format: double  

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

