---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.hflip"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: hflip  
media types:
Video  
description: Horizontally flip the input video.  
version: Lavfi7.110.100  
creator: libavfilter maintainers  

## Parameters

### av.threads

  
description:
Maximum number of threads  
type: integer  
readonly: no  
required: no  
minimum: 0  
default: 0  

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

