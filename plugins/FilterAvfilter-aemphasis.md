---
layout: standard
title: Documentation
wrap_title: "Filter: avfilter.aemphasis"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: aemphasis  
media types:
Audio  
description: Audio emphasis.  
version: Lavfi7.110.100  
creator: libavfilter maintainers  

## Parameters

### av.level_in

  
description:
set input gain  
type: float  
readonly: no  
required: no  
minimum: 0  
maximum: 64  
default: 1  
format: double  

### av.level_out

  
description:
set output gain  
type: float  
readonly: no  
required: no  
minimum: 0  
maximum: 64  
default: 1  
format: double  

### av.mode

  
description:
set filter mode  
type: string  
readonly: no  
required: no  
format: integer or keyword  
values:  

* reproduction
* production

### av.type

  
description:
set filter type  
type: string  
readonly: no  
required: no  
format: integer or keyword  
values:  

* col
* emi
* bsi
* riaa
* cd
* 50fm
* 75fm
* 50kf
* 75kf

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

