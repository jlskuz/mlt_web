---
layout: standard
title: Documentation
wrap_title: "Filter: bass"
category: plugin
---
* TOC
{:toc}

## Plugin Information

title: bass  
media types:
Audio  
description: Process audio using a SoX effect.  
version: 1  
creator: Dan Dennedy  
copyright: Meltytech, LLC  
license: LGPL  
URL: [http://sox.sourceforge.net/](http://sox.sourceforge.net/)  

## Bugs

* Some effects are stereo only, but MLT processes each channel separately.
* Some effects have a temporal side-effect that do not work well.


## Parameters

### argument

title: Options    
type: string  
readonly: no  
required: no  
format: gain [frequency(100) [width[s|h|k|q|o]]\(0.5s)]  

