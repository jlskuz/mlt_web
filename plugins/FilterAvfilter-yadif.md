---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.yadif"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: yadif  
media types:
Video  
description: Deinterlace the input image.  
version: Lavfi7.40.101  
creator: libavfilter maintainers  

## Parameters

### av.mode

  
description:
specify the interlacing mode  
type: string  
readonly: no  
required: no  
format: integer or keyword  
values:  

* send_frame
* send_field
* send_frame_nospatial
* send_field_nospatial

### av.parity

  
description:
specify the assumed picture field parity  
type: string  
readonly: no  
required: no  
format: integer or keyword  
values:  

* tff
* bff
* auto

### av.deint

  
description:
specify which frames to deinterlace  
type: string  
readonly: no  
required: no  
format: integer or keyword  
values:  

* all
* interlaced

### av.threads

  
description:
Maximum number of threads  
type: integer  
readonly: no  
required: no  
minimum: 0  
default: 0  

