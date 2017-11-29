---
title:  "CAPAM workshop, CJFAS issue, and more updates"
excerpt: "CAPAM workshop, and updates"
layout: default
---

Hi all,

A few updates since my last email (back in May!):

1.  The CAPAM workshop on spatio-temporal analysis of fishery catch and effort data, Feb. 26-March 2 in La Jolla is now accepting abstracts (http://www.capamresearch.org/sites/default/files/CAPAM_spatio-temporal_modelling_workshop_Anouncement_2.pdf).  It should be a great meeting!  We're looking for case-studies on spatio-temporal models and fishery CPUE analysis and hope people present.

2.  I'll be teaching a 1-week workshop, Jan. 29-Feb 1 in Seattle, on using VAST for generating indices from trawl and acoustic data using AFSC surveys.  Please add your name online (https://docs.google.com/document/d/1z1MSlE0pvj6HrhNTRd5zD5L1wxBLLi1l4Zu9Hv7hxV0/edit?usp=sharing) if you want to receive information to remotely connect

3.  The CJFAS special issue on spatial models is now out (http://www.nrcresearchpress.com/toc/cjfas/74/11).  It has many examples of spatially-structured population models, plus how to integrate with spatio-temporal delta-models.

4.  A new "Poisson-link delta-model" is now available in VAST, using `ObsModel[2]=1`, which approximates a Tweedie distribution and is more interpretable than the conventional delta-model (http://www.nrcresearchpress.com/doi/abs/10.1139/cjfas-2017-0266#.Wh7VUIanFaQ).  Comparison using >100 stocks shows that it often fits better than the conventional delta-model.

5.  I'm maintaining a list of stock assessments, reports, and journal articles using VAST or its precursors (https://github.com/nwfsc-assess/geostatistical_delta-GLMM/wiki/Applications). Please email me to add things, and its a good place to check to keep up with developments and applications.

Jim