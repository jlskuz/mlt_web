---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.cropdetect"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: cropdetect  
media types:
Video  
description: Auto-detect crop size.  
version: Lavfi7.110.100  
creator: libavfilter maintainers  

## Parameters

### av.limit

  
description:
Threshold below which the pixel is considered black  
type: float  
readonly: no  
required: no  
minimum: 0  
maximum: 65535  
default: 0.0941176  

### av.round

  
description:
Value by which the width/height should be divisible  
type: integer  
readonly: no  
required: no  
minimum: 0  
default: 16  

### av.reset

  
description:
Recalculate the crop area after this many frames  
type: integer  
readonly: no  
required: no  
minimum: 0  
default: 0  

### av.skip

  
description:
Number of initial frames to skip  
type: integer  
readonly: no  
required: no  
minimum: 0  
default: 2  

### av.reset_count

  
description:
Recalculate the crop area after this many frames  
type: integer  
readonly: no  
required: no  
minimum: 0  
default: 0  

### av.max_outliers

  
description:
Threshold count of outliers  
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

