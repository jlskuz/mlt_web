---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.weave"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: weave  
media types:
Video  
description: Weave input video fields into frames.  
version: Lavfi7.110.100  
creator: libavfilter maintainers  

## Parameters

### av.first_field

  
description:
set first field  
type: string  
readonly: no  
required: no  
format: integer or keyword  
values:  

* top
* t
* bottom
* b

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

