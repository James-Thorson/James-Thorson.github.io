---
title:  "Introducing resources in FishStats"
excerpt: "Tutorials for single and multispecies models"
layout: default
---

FishStats compiles different tools for harmonizing data for marine fishes worldwide, analyzing data to estimate abundance, distribution shift, range expansion, and spatial overlap, and also visualize results.  Current tools include:

1.  a markdown [tutorial](https://github.com/nwfsc-assess/geostatistical_delta-GLMM/blob/master/examples/SpatialDeltaGLMM_example.pdf) for a single-species spatio-temporal model, [SpatialDeltaGLMM](https://github.com/nwfsc-assess/geostatistical_delta-GLMM).  SpatialDeltaGLMM can now calculate range expansion/contraction from a new [ProcB paper](http://rspb.royalsocietypublishing.org/content/283/1840/20161853.abstract), as well as distribution shifts from a [MEE paper](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12567/full), in addition to previous abundance-index estimates from an [ICESJMS paper](http://icesjms.oxfordjournals.org/content/72/5/1297).

2.  a markdown [tutorial](https://github.com/James-Thorson/VAST/blob/master/examples/VAST--multispecies_example.pdf) for a multispecies model [VAST](https://github.com/James-Thorson/VAST).   VAST is identical to SpatialDeltaGLMM for single-species data (including indices, range shift, and range expansion metrics), but can also estimate community dynamics via spatial dynamic factor analysis from a [Global Ecology Biogreography paper](http://onlinelibrary.wiley.com/doi/10.1111/geb.12464/full), or control for fisher targeting using multispecies fishery data to estimate abundance from a [CJFAS paper](http://www.nrcresearchpress.com/doi/abs/10.1139/cjfas-2015-0598).  

3.  [FishViz.org](http://www.fishviz.org/) visualizes model output from SpatialDeltaGLMM applied to fishery data fishery data for >400 species in 15 regions worldwide at www.FishViz.org (including all groundfishes in Alaska and West Coast regions).  

4.  FishStats now has a [FishStats-listserv](https://groups.google.com/d/forum/fishstats-listserv)  