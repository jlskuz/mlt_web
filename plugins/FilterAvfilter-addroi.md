---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.addroi"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: addroi  
media types:
Video  
description: Add region of interest to frame.  
version: Lavfi7.110.100  
creator: libavfilter maintainers  

## Parameters

### av.x

  
description:
Region distance from left edge of frame.  
type: string  
readonly: no  
required: no  
default: '0'  

### av.y

  
description:
Region distance from top edge of frame.  
type: string  
readonly: no  
required: no  
default: '0'  

### av.w

  
description:
Region width.  
type: string  
readonly: no  
required: no  
default: '0'  

### av.h

  
description:
Region height.  
type: string  
readonly: no  
required: no  
default: '0'  

### av.qoffset

  
description:
Quantisation offset to apply in the region.  
type: string  
readonly: no  
required: no  
format: numerator/denominator  

### av.clear

  
description:
Remove any existing regions of interest before adding the new one.  
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

