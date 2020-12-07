---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.biquad"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: biquad  
media types:
Audio  
description: Apply a biquad IIR filter with the given coefficients.  
version: Lavfi7.85.100  
creator: libavfilter maintainers  

## Parameters

### av.a0

  
type: float  
readonly: no  
required: no  
minimum: -2147480000.0  
maximum: 2147480000.0  
default: 1  
format: double  

### av.a1

  
type: float  
readonly: no  
required: no  
minimum: -2147480000.0  
maximum: 2147480000.0  
default: 0  
format: double  

### av.a2

  
type: float  
readonly: no  
required: no  
minimum: -2147480000.0  
maximum: 2147480000.0  
default: 0  
format: double  

### av.b0

  
type: float  
readonly: no  
required: no  
minimum: -2147480000.0  
maximum: 2147480000.0  
default: 0  
format: double  

### av.b1

  
type: float  
readonly: no  
required: no  
minimum: -2147480000.0  
maximum: 2147480000.0  
default: 0  
format: double  

### av.b2

  
type: float  
readonly: no  
required: no  
minimum: -2147480000.0  
maximum: 2147480000.0  
default: 0  
format: double  

### av.mix

  
description:
set mix  
type: float  
readonly: no  
required: no  
minimum: 0  
maximum: 1  
default: 1  
format: double  

### av.m

  
description:
set mix  
type: float  
readonly: no  
required: no  
minimum: 0  
maximum: 1  
default: 1  
format: double  

### av.channels

  
description:
set channels to filter  
type: string  
readonly: no  
required: no  

### av.c

  
description:
set channels to filter  
type: string  
readonly: no  
required: no  

### av.normalize

  
description:
normalize coefficients  
type: string  
readonly: no  
required: no  

### av.n

  
description:
normalize coefficients  
type: string  
readonly: no  
required: no  

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

