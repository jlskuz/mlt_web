---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.lut1d"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: lut1d  
media types:
Video  
description: Adjust colors using a 1D LUT.  
version: Lavfi7.40.101  
creator: libavfilter maintainers  

## Parameters

### av.file

  
description:
set 1D LUT file name  
type: string  
readonly: no  
required: no  

### av.interp

  
description:
select interpolation mode  
type: string  
readonly: no  
required: no  
format: integer or keyword  
values:  

* nearest
* linear
* cubic

### av.threads

  
description:
Maximum number of threads  
type: integer  
readonly: no  
required: no  
minimum: 0  
default: 0  

