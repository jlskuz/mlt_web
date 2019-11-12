---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.silencedetect"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: silencedetect  
media types:
Audio  
description: Detect silence.  
version: Lavfi7.57.100  
creator: libavfilter maintainers  

## Parameters

### av.n

  
description:
set noise tolerance  
type: float  
readonly: no  
required: no  
minimum: 0  
default: 0.001  
format: double  

### av.noise

  
description:
set noise tolerance  
type: float  
readonly: no  
required: no  
minimum: 0  
default: 0.001  
format: double  

### av.d

  
description:
set minimum duration in seconds  
type: float  
readonly: no  
required: no  
minimum: 0  
maximum: 86400  
default: 2  
format: double  

### av.duration

  
description:
set minimum duration in seconds  
type: float  
readonly: no  
required: no  
minimum: 0  
maximum: 86400  
default: 2  
format: double  

### av.mono

  
description:
check each channel separately  
type: string  
readonly: no  
required: no  

### av.m

  
description:
check each channel separately  
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

