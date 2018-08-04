Collection of links to resources for reproducible computing and predictive modeling applications
================

Data infrastructure
===================

-   Ke Shen and Paul Grech: Medium blog entry ["Data Scientist's Toolbox for Data Infrastructure I"](https://medium.com/@TheLaddersEng/data-scientists-toolbox-for-data-infrastructure-i-e25391f145a3)

Spatial data integration and processing
---------------------------------------

-   The future of R spatial

OpenCPU
=======

-   Jeroen Ooms (Submitted on 4 Jun 2014): ["The OpenCPU System: Towards a Universal Interface for Scientific Computing through Separation of Concerns"](https://arxiv.org/abs/1406.4806) arXiv:1303.4808

-   Quora: ["How do plumber and OpenCPU compare when it comes to deploying ML models?"](https://www.quora.com/How-do-plumber-and-OpenCPU-compare-when-it-comes-to-deploying-ML-models)

OpenCPU core components
-----------------------

-   Official website: <https://opencpu.org>
    -   [opencpu.js JavaScript client library](https://www.opencpu.org/jslib.html): Wrappers for calling R from within a web page
    -   [OpenCPU HTTP API documentation](https://www.opencpu.org/api.html)
    -   [The OpenCPU Server PDF Manual](https://opencpu.github.io/server-manual/opencpu-server.pdf)

OpenCPU example applications
----------------------------

-   [OpenCPU official example apps](https://www.opencpu.org/apps.html)
-   [openCPU GUI for the spdynmod library (github)](https://github.com/javimarlop/spdynmodocpu) || [try online](http://95.85.28.225/ocpu/library/spdynmodocpu/www) || [slides](http://r-es.org/7jornadasR/ponencias/juan_arevalo.pdf)
    -   Martínez-López, J., Martínez-Fernández, J., Naimi, B., Carreño, M.F., Esteve, M.A., 2015. An open-source spatio-dynamic wetland model of plant community responses to hydrological pressures. Ecological Modelling 306, 326–333.
-   Yves Crutain: ["Dashboarding with Flexdashboard and Opencpu"](http://data-laborer.eu/r/Flexocpu/) || Combing shiny, flexdashboard and openCPU
    -   Example use of openCPU in a flexdashboard: [github](https://github.com/YvesCR/flexocpu) || [online app](https://yvescr.ocpu.io/flexocpu/www/)
    -   [RStudio: "Using shiny with flexdashboard"](https://rmarkdown.rstudio.com/flexdashboard/shiny.html)
-   Roland Hansson: [GeoTuple: open cloud based platform for geospatial analysis with R](http://geotuple.org/) || [github](https://github.com/rhansson/geotuple)
-   Mark Edmondson: [Creating a content recommendation engine using R, OpenCPU and GTM || Proof of concept for connecting Google Tag Manager to R](http://code.markedmondson.me/predictClickOpenCPU/)

Asynchronous programming, promises/futures
==========================================

-   CRAN vignette promise package: ["Launching tasks with future"](https://cran.r-project.org/web/packages/promises/vignettes/futures.html)
-   -   Detect bottlenecks to decide which slow operation to wrap into a future: <https://rstudio.github.io/profvis/>
-   Joe Cheng (rstudio::conf2018): ["R promises: A promising approach for more responsive Shiny apps"](https://speakerdeck.com/jcheng5/r-promises)
-   Henrik Bentsson: future and related R packages
    -   [future: Unified Parallel and Distributed Processing in R for Everyone (github)](https://github.com/HenrikBengtsson/future)
    -   [Delayed Future(Slides from eRum 2018)](https://www.jottr.org/2018/06/18/future-erum2018-slides/) || [Future: Parallel & Distributed Processing in R for Everyone](https://www.jottr.org/presentations/erum2018/bengtssonh_20180516-erum2018)
-   github.com/cywhale/ODB: [Code for R shiny app which tests newly implemented promises and future features](https://github.com/cywhale/ODB/blob/master/shiny_async_test/app.R)
