---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.bbox"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: bbox  
media types:
Video  
description: Compute bounding box for each frame.  
version: Lavfi7.110.100  
creator: libavfilter maintainers  

## Parameters

### av.min_val

  
description:
set minimum luminance value for bounding box  
type: integer  
readonly: no  
required: no  
minimum: 0  
maximum: 65535  
default: 16  

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

