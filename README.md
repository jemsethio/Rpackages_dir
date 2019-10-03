[]
  - [My directory of R packages for data analysis and visualization,
    Bayesian statistics, mapping, GIS, climate, Species Distribution
    Modelling, ecology, biogeography, evolution, reproducible
    science…](#my-directory-of-r-packages-for-data-analysis-and-visualization-bayesian-statistics-mapping-gis-climate-species-distribution-modelling-ecology-biogeography-evolution-reproducible-science)
  - [Data sources](#data-sources)
  - [Data management](#data-management)
  - [General statistics](#general-statistics)
      - [Ordination & Multivariate
        Analysis](#ordination-multivariate-analysis)
      - [Survival analysis](#survival-analysis)
      - [Regression tools](#regression-tools)
      - [Bayesian/MCMC](#bayesianmcmc)
  - [Plotting & Visualisation](#plotting-visualisation)
      - [GGPLOT2](#ggplot2)
      - [Colour](#colour)
  - [Reproducible Research - Report
    generation](#reproducible-research---report-generation)
  - [Parallelisation & Big Data](#parallelisation-big-data)
  - [Niche & Species Distribution
    Modelling](#niche-species-distribution-modelling)
      - [Occupancy modelling](#occupancy-modelling)
  - [Remote Sensing](#remote-sensing)
  - [Climate](#climate)
  - [GIS/spatial functionality](#gisspatial-functionality)
  - [Spatial Analysis](#spatial-analysis)
  - [Networks](#networks)
  - [Phylogenetics, phylogeography & comparative
    analysis](#phylogenetics-phylogeography-comparative-analysis)
  - [Palaeoecology](#palaeoecology)
  - [Dendrochronology](#dendrochronology)
  - [Ecological analyses
    (miscellaneous)](#ecological-analyses-miscellaneous)
  - [Miscellaneous](#miscellaneous)
  - [R programming](#r-programming)

## My directory of R packages for data analysis and visualization, Bayesian statistics, mapping, GIS, climate, Species Distribution Modelling, ecology, biogeography, evolution, reproducible science…

[F. Rodriguez-Sanchez](http://bit.ly/frod_san)

Updated 2019-10-03

These are packages that I often use or, alternatively, I need only
rarely but don’t want to forget about. Of course, there are many other
useful packages out there (e.g. at
[CRAN](http://cran.r-project.org/web/packages/available_packages_by_name.html)
or
[GitHub](https://github.com/search?q=package&type=Repositories&ref=advsearch&l=R).
Check also [CRAN task views](http://cran.r-project.org/web/views/).

## Data sources

Check [CRAN Task View on Web
technologies](http://cran.r-project.org/web/views/WebTechnologies.html).

## Data management

Check out this great cheatsheet: [Data wrangling with dplyr and
tidyr](http://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

  - [rio](https://cran.r-project.org/package=rio) A Swiss-Army Knife for
    Data I/O
  - [tidyr](https://cran.r-project.org/package=tidyr) Reshape data
  - [reshape2](https://cran.r-project.org/package=reshape2) Reshape data
    from long to wide format and vice versa
  - [dplyr](https://cran.r-project.org/package=dplyr) Data wrangling
  - [data.table](https://cran.r-project.org/package=data.table) Tools
    for managing data frames
  - [gdata](https://cran.r-project.org/package=gdata) Data manipulation
  - [Hmisc](https://cran.r-project.org/package=Hmisc) Frank Harrell’s
    miscellaneous tools
  - [Kmisc](https://cran.r-project.org/package=Kmisc) Data reshaping,
    table and plot generation from RMarkdown
  - [lubridate](https://cran.r-project.org/package=lubridate) Dates and
    times
  - [multitable](https://cran.r-project.org/package=multitable)
    Manipulate multiple arrays
  - [datacheck](https://cran.r-project.org/package=datacheck) Tools for
    checking data consistency
  - [tabplot](https://cran.r-project.org/package=tabplot) Large datasets
    viz.
  - [tabplotd3](https://cran.r-project.org/package=tabplotd3)
    Interactive
  - [tableplot](https://cran.r-project.org/package=tableplot)
  - [taRifx](http://cran.r-project.org/web/packages/taRifx/index.html)
    Useful
    functions
  - [DescTools](http://cran.r-project.org/web/packages/DescTools/index.html)
    Many useful functions
  - [summarytools](https://cran.r-project.org/package=summarytools)
    Quickly summarize dataframes (inc. markdown output)

## General statistics

### Ordination & Multivariate Analysis

Check also
[Environmetrics](http://cran.r-project.org/web/views/Environmetrics.html)
and
[Multivariate](http://cran.r-project.org/web/views/Multivariate.html)
CRAN Task Views.

  - [vegan](https://cran.r-project.org/package=vegan)
  - [ade4](http://cran.r-project.org/web/packages/ade4/index.html)
    Multivariate data analysis and display
  - [dave](https://cran.r-project.org/package=dave) Data Analysis in
    Vegetation Ecology
  - [ecodist](https://cran.r-project.org/package=ecodist)
    Dissimilarity-based analysis (ordination, Mantel tests…)
  - [labdsv](https://cran.r-project.org/package=labdsv) Includes
    plotting functions
  - [mvabund](https://cran.r-project.org/package=mvabund) Analysing
    multivariate data (upscaling from individual species models)
  - [boral](https://cran.r-project.org/package=boral) Bayesian
    ordination and regression analysis
  - [eigenprcomp](http://cran.r-project.org/web/packages/eigenprcomp/)
    Computes confidence intervals for the proportion explained by the
    first 1,2,k principal components

### Survival analysis

  - [survival](https://cran.r-project.org/package=survival)
  - [survMisc](https://cran.r-project.org/package=survMisc)
  - [coxme](https://cran.r-project.org/package=coxme) Mixed-effects cox
    regression
  - [rawr](https://cran.r-project.org/package=rawr) Plotting functions:
    kmplot & ggsurv

### Regression tools

  - [aod](https://cran.r-project.org/package=aod) Analysis of
    Overdispersed
    data
  - [AICcmodavg](http://cran.r-project.org/web/packages/AICcmodavg/index.html)
    Model selection and multimodel inference
  - [arm](https://cran.r-project.org/package=arm) Gelman’s package:
    includes bayesglm, sim, coefplot…
  - [bbmle](https://cran.r-project.org/package=bbmle) Tools for MLE
  - [binomTools](https://cran.r-project.org/package=binomTools)
    Diagnostics for binomial regression
  - [car](https://cran.r-project.org/package=car) Regression tools
  - [coefplot](https://cran.r-project.org/package=coefplot) Plot model
    coefficients
  - [confReg](https://cran.r-project.org/package=confReg) Estimating
    confidence of individual regression predictions
  - [COUNT](https://cran.r-project.org/package=COUNT) Regression models
    for count data (Poisson, Negative Binomial)
  - [DAAG](https://cran.r-project.org/package=DAAG) Some regression
    tools from the book ‘Data Analysis and Graphics using R’
  - [dhglm](https://cran.r-project.org/package=dhglm) Hierarchical GLMs
    with random effects in both the mean and dispersion components
  - [dynlm](https://cran.r-project.org/package=dynlm) Dynamic linear
    models and time series regression
  - [earth](https://cran.r-project.org/package=earth) Multivariate
    Adaptive Regression Splines
  - [effects](https://cran.r-project.org/package=effects) Displays
    effects estimated from regression models
  - [emdbook](https://cran.r-project.org/package=emdbook) Tools from
    ‘Ecological Models and Data’ (inc. several plotting functions)
  - [fit.models](https://cran.r-project.org/package=fit.models) Compare
    results from different models
  - [FME](https://cran.r-project.org/package=FME) Modelling tools
  - [gam](https://cran.r-project.org/package=gam) Generalised Additive
    Models (GAMs)
  - [gamm4](https://cran.r-project.org/package=gamm4) GAMMs
  - [gbm](https://cran.r-project.org/package=gbm) Generalised Boosted
    regression models
  - [gee](https://cran.r-project.org/package=gee) Generalized Estimating
    Equations
  - [glm2](https://cran.r-project.org/package=glm2) To fit GLMs with
    convergence problems
  - [MuMIn](https://cran.r-project.org/package=MuMIn) Model selection
    and averaging
  - [glmulti](https://cran.r-project.org/package=glmulti) Model
    selection and multimodel inference
  - [gnm](https://cran.r-project.org/package=gnm) Generalized nonlinear
    models
  - [heatmapFit](https://cran.r-project.org/package=heatmapFit) Checking
    logistic regression goodness of fit
  - [hier.part](https://cran.r-project.org/package=hier.part) Variance
    partitioning to assess ‘importance’ of predictors. See also
    `relaimpo`.
  - [relaimpo](https://cran.r-project.org/package=relaimpo) Relative
    importance of predictors
  - [nlme](https://cran.r-project.org/package=nlme) Mixed models
  - [lme4](https://cran.r-project.org/package=lme4) Mixed models
  - [pamm](https://cran.r-project.org/package=pamm) Power analysis for
    mixed models
  - [odprism](https://cran.r-project.org/package=odprism) Power analysis
    for mixed models
  - [likelihood](https://cran.r-project.org/package=likelihood) Maximum
    Likelihood Estimation
  - [lmtest](https://cran.r-project.org/package=lmtest) Diagnostic
    checks for linear regression
  - [MARSS](https://cran.r-project.org/package=MARSS) Multivariate
    Autoregressive State-Space Modeling
  - [MCMCglmm](https://cran.r-project.org/package=MCMCglmm) Mixed models
    fitted by MCMC
  - [mgcv](https://cran.r-project.org/package=mgcv) GAM fitting
  - [miscF](https://cran.r-project.org/package=miscF) Multivariate
    Normal regression, spatial Bayesian mixed models, piecewise
    regression…
  - [mlogit](https://cran.r-project.org/package=mlogit) Multinomial
    regression
  - [mvinfluence](https://cran.r-project.org/package=mvinfluence)
    Influence Measures and Diagnostic Plots for Multivariate Linear
    Models
  - [msm](https://cran.r-project.org/package=msm) Multi-state Markov and
    hidden Markov models in continuous time
  - [PCovR](https://cran.r-project.org/package=PCovR) Principal
    Covariates Regression (Reducing collinear predictor variables to a
    few components and regressing on them)
  - [HLMdiag](https://cran.r-project.org/package=HLMdiag) Diagnostic
    tools for hierarchical models (fitted with lme4)
  - [stremo](https://cran.r-project.org/package=stremo) Learning
    Structural Equation Models
  - [rockchalk](https://cran.r-project.org/package=rockchalk) Regression
    Estimation and Presentation
  - [R2STATS](https://cran.r-project.org/package=R2STATS) GUI for
    fitting and comparing GLM and GLMM in
    R
  - [LMERConvenienceFunctions](https://cran.r-project.org/package=LMERConvenienceFunctions)
  - [R2admb](https://cran.r-project.org/package=R2admb)
  - [rms](https://cran.r-project.org/package=rms) Regression modeling
    strategies
  - [Zelig](https://cran.r-project.org/package=Zelig)

### Bayesian/MCMC

Check also [Bayesian CRAN Task
View](http://cran.r-project.org/web/views/Bayesian.html).

  - [rstanarm](https://cran.r-project.org/package=rstanarm)
  - [blme](https://cran.r-project.org/package=blme) Bayesian multilevel
    models
  - [BMA](https://cran.r-project.org/package=BMA) Model averaging
  - [dclone](https://cran.r-project.org/package=dclone) Data cloning and
    MCMC tools (inc. JAGS functions)
  - [dcmle](https://cran.r-project.org/package=dcmle) Hierarchical
    models through data cloning
  - [dlm](https://cran.r-project.org/package=dlm) Dynamic models and
    MCMC tools
  - [dlmodeler](https://cran.r-project.org/package=dlmodeler)
    State-space modelling
  - [sspir](https://cran.r-project.org/package=sspir) State-space models
  - [MCMCglmm](https://cran.r-project.org/package=MCMCglmm) Mixed models
    fitted by MCMC
  - [RSGHB](https://cran.r-project.org/package=RSGHB) Hierarchical Bayes
    models
  - [bayespref](https://cran.r-project.org/package=bayespref) Analysis
    of count data
  - [predcomps](https://github.com/dchudz/predcomps) Average Predictive
    Comparisons

#### Generic MCMC samplers

  - [adaptMCMC](http://cran.r-project.org/web/packages/adaptMCMC/index.html)
    Generic MCMC sampler
  - [BRugs](https://cran.r-project.org/package=BRugs) Interface to
    OpenBUGS
  - [BayesX](https://cran.r-project.org/package=BayesX) Structured
    Additive Regression
  - [R2BayesX](https://cran.r-project.org/package=R2BayesX)
  - [rjags](https://cran.r-project.org/package=rjags)
  - [runjags](https://cran.r-project.org/package=runjags)
  - [R2jags](https://cran.r-project.org/package=R2jags)
  - [jagsUI](https://cran.r-project.org/package=jagsUI)
  - [R2OpenBUGS](https://cran.r-project.org/package=R2OpenBUGS)
  - [R2WinBUGS](https://cran.r-project.org/package=R2WinBUGS)
  - [rstan](https://cran.r-project.org/package=rstan)
  - [filzbach](https://cran.r-project.org/package=filzbach)
  - [iBUGS](https://cran.r-project.org/package=iBUGS) Interface to
    BUGS/JAGS
  - [rube](http://stat.cmu.edu/~hseltman/rube/)
  - [INLA](https://cran.r-project.org/package=INLA) Integrated Nested
    Laplace Approximation
  - [LaplacesDemon](https://cran.r-project.org/package=LaplacesDemon)
  - [LearnBayes](https://cran.r-project.org/package=LearnBayes)
  - [MCMCpack](https://cran.r-project.org/package=MCMCpack) MCMC
    samplers
  - [MHAdative](https://cran.r-project.org/package=MHAdative) MCMC
    sampler
  - [glmmBUGS](https://cran.r-project.org/package=glmmBUGS)
  - [mcmc](https://cran.r-project.org/package=mcmc)
  - [datalist](http://cran.r-project.org/web/packages/datalist/index.html)

#### MCMC diagnostics & plotting

  - [coda](https://cran.r-project.org/package=coda) MCMC output analysis
  - [boa](https://cran.r-project.org/package=boa) Analyses of MCMC
    output (like `coda`)
  - [ggmcmc](https://cran.r-project.org/package=ggmcmc) Graphic analysis
    of MCMC output
  - [mcmcmplots](https://cran.r-project.org/package=mcmcplots) Plot MCMC
    output
  - [plotMCMC](https://cran.r-project.org/package=plotMCMC) Diagnostic
    plots
  - [bmk](https://cran.r-project.org/package=bmk) MCMC diagnostics
  - [superdiag](https://cran.r-project.org/package=superdiag) testing
    MCMC noncovergence
  - [shinyStan](https://cran.r-project.org/package=shinyStan)
  - [MCMCvis](https://cran.r-project.org/package=MCMCvis)
  - [rwty](https://cran.r-project.org/package=rwty)
  - [dMCMC](https://github.com/MarcoDVisser/dMCMC)
  - [bayesplot](https://github.com/stan-dev/bayesplot)

#### Spatial Bayes

  - [CARBayes](https://cran.r-project.org/package=CARBayes) Spatial
    models with CAR
  - [spBayes](https://cran.r-project.org/package=spBayes) spatial
    Bayes
  - [geoCount](http://cran.r-project.org/web/packages/geoCount/index.html)
    generalized linear spatial models

#### ABC

  - [abc](http://cran.r-project.org/web/packages/abc/index.html)
    Approximate Bayesian Computation
  - [easyABC](https://cran.r-project.org/package=easyABC) Approximate
    Bayesian Computation

## Plotting & Visualisation

Check also [CRAN Task View on
Graphics](http://cran.r-project.org/web/views/Graphics.html).

  - [denstrip](https://cran.r-project.org/package=denstrip) Plotting
    distributions (w uncertainty)
  - [visualize](https://cran.r-project.org/package=visualize) Graph
    Probability Distributions
  - [fanplot](https://cran.r-project.org/package=fanplot) Visualise
    sequential probability distributions
  - [diagram](https://cran.r-project.org/package=diagram) Networks, flow
    diagrams, etc
  - [beanplot](https://cran.r-project.org/package=beanplot) Bean plots
  - [vioplot](https://cran.r-project.org/package=vioplot) Violin plots
  - [viopoints](https://cran.r-project.org/package=viopoints) 1-D
    Scatter Plots with Jitter Using Kernel Density Estimates
  - [dagR](https://cran.r-project.org/package=dagR) Directed Acyclic
    graphs (DAGs)
  - [effects](https://cran.r-project.org/package=effects) Displays
    effects estimated from regression models
  - [coefplot](https://cran.r-project.org/package=coefplot) Plot model
    coefficients
  - [plotmo](https://cran.r-project.org/package=plotmo) Plot model
    responses
  - [corrgram](https://cran.r-project.org/package=corrgram) Plot
    correlation matrix
  - [gclus](https://cran.r-project.org/package=gclus) Clustering
    graphics
  - [vcd](https://cran.r-project.org/package=vcd) Viz categorical data
  - [extracat](https://cran.r-project.org/package=extracat) Viz
    categorical data
  - [plot3d](http://cran.r-project.org/web/packages/plot3D/index.html)
    Plotting multi-dimensional data
  - [VizOR](http://cran.r-project.org/web/packages/VizOR/index.html)
    visualization tools for complex observational data
  - [GrapheR](https://cran.r-project.org/package=GrapheR) GUI for base
    plots

### GGPLOT2

  - [ggplot2](https://cran.r-project.org/package=ggplot2)

  - [GGally](https://cran.r-project.org/package=GGally) extension to
    ggplot

  - [ggsubplot](https://cran.r-project.org/package=ggsubplot) Embedding
    subplots within plots

  - [ggthemes](https://cran.r-project.org/package=ggthemes) Extra
    themes, scales and geoms for ggplot

  - [gplot2bdc](https://github.com/briandconnelly/ggplot2bdc)

  - [ggtern](http://www.ggtern.com/) Ternary diagrams

  - [ggthemr](https://github.com/cttobin/ggthemr) Extra themes for
    ggplot2

  - [plotly](https://github.com/ropensci/plotly) R interface to plotly

  - [googleVis](https://cran.r-project.org/package=googleVis) Using
    google chart tools

  - [rCharts](https://cran.r-project.org/package=rCharts) Interactive
    charts

  - [lattice](https://cran.r-project.org/package=lattice) Multivariate
    plots

  - [manipulate](https://cran.r-project.org/package=manipulate)
    Interactive plots

  - [misc3d](https://cran.r-project.org/package=misc3d) 3D plots

  - [mvtsplot](https://cran.r-project.org/package=mvtsplot) Multivariate
    time series plot

  - [pca3d](https://cran.r-project.org/package=pca3d) Three dimensional
    PCA plots

  - [longCatEDA](https://cran.r-project.org/package=longCatEDA) Plot
    Categorical Longitudinal and Time-Series Data

  - [squash](https://cran.r-project.org/package=squash) Color-based
    plots for multivariate visualization

  - [tourr](https://cran.r-project.org/package=tourr)

  - [latticist](https://cran.r-project.org/package=latticist) GUI for
    graphic exploratory data analysis using lattice

  - [tfplot](https://cran.r-project.org/package=tfplot) Plot time series

  - [pathdiagram](http://cran.r-project.org/web/packages/pathdiagram/)

  - [RIGHT](https://cran.r-project.org/package=RIGHT) Interactive
    graphics via HTML

  - [clickme](https://github.com/nachocab/clickme) Interactive plots

  - [animation](https://cran.r-project.org/package=animation) Create
    animations

  - [calibrate](https://cran.r-project.org/package=calibrate) Axes
    calibration

  - [labeling](https://cran.r-project.org/package=labeling) Axis
    labeling

  - [directlabels](https://cran.r-project.org/package=directlabels)
    Labels for multicolor plots. See also `Hmisc:::labcurve`.

  - [gplots](https://cran.r-project.org/package=gplots) Useful plotting
    tools

  - [magicaxis](https://cran.r-project.org/package=magicaxis) Pretty
    scientific plots (e.g. log
    scales)

  - [PlotRegionHighlighter](https://cran.r-project.org/package=PlotRegionHighlighter)
    Creates an envelope that surrounds a set of
    points

  - [compactr](http://cran.us.r-project.org/web/packages/compactr/index.html)
    Plots with compact axis notation

  - [plotflow](https://github.com/trinker/plotflow) Useful plotting
    functions

  - [sendplot](https://cran.r-project.org/package=sendplot) Interactive
    plots with tool-tip content

  - [zoom](https://cran.r-project.org/package=zoom) Allow to
    zoom/navigate in any plot.

  - [Hmisc](https://cran.r-project.org/package=Hmisc)

  - [epade](https://cran.r-project.org/package=epade) Easy plots

  - [prettyGraphs](https://cran.r-project.org/package=prettyGraphs)
    Publication-quality graphics.

  - [scagnostics](https://cran.r-project.org/package=scagnostics)
    Scatterplot diagnostics

### Colour

  - [colorRamps](https://cran.r-project.org/package=colorRamps) Colour
    palettes

  - [RColorBrewer](https://cran.r-project.org/package=RColorBrewer)

  - [colorspace](https://cran.r-project.org/package=colorspace) HCL
    (perceptually-based) palettes

  - [colortools](https://cran.r-project.org/package=colortools)

  - [plotKML](https://cran.r-project.org/package=plotKML) Colour
    palettes for mapping

  - [gplots](https://cran.r-project.org/package=gplots) Rich.colors
    palettes

  - [dataview](https://cran.r-project.org/package=dataview)

  - [tabplot](https://cran.r-project.org/package=tabplot) Large datasets
    viz.

  - [tabplotd3](https://cran.r-project.org/package=tabplotd3)
    Interactive

  - [R2SWF](https://cran.r-project.org/package=R2SWF) Convert R graphics
    to Flash

  - [sendplot](https://cran.r-project.org/package=sendplot) Send
    interactive plots with tooltip content

  - [sjPlot](https://cran.r-project.org/package=sjPlot)

  - [squash](https://cran.r-project.org/package=squash) Color-based
    plots for multivariate visualization

## Reproducible Research - Report generation

Check also CRAN Task View on [Reproducible
Research](http://cran.r-project.org/web/views/ReproducibleResearch.html).

  - [brew](https://cran.r-project.org/package=brew)
  - [knitr](https://cran.r-project.org/package=knitr) Dynamic report
    generation
  - [knitrBootstrap](https://github.com/jimhester/knitrBootstrap) create
    bootstrap styled HTML reports from Rmarkdown
  - [reports](https://cran.r-project.org/package=reports) writing
    reports and presentations
  - [repmis](https://cran.r-project.org/package=repmis)
  - [rapport](http://cran.r-project.org/web/packages/rapport/index.html)
    report templating system
  - [pander](https://cran.r-project.org/package=pander) Exploits pandoc
    to convert among multiple formats
  - [stargazer](https://cran.r-project.org/package=stargazer) Easily
    create tables with regression outputs (directly from model objects)
  - [rtf](http://cran.r-project.org/web/packages/rtf/index.html) Produce
    Rich Text Format documents from R
  - [R2HTML](http://cran.r-project.org/web/packages/R2HTML/index.html)
    HTML reports from R
  - [xtable](http://cran.r-project.org/web/packages/xtable/index.html)
    Export R objects to HTML tables
  - [R2wd](https://cran.r-project.org/package=R2wd) Write MS-Word
    documents from
    R
  - [rmarkdown](https://cran.r-project.org/package=rmarkdown)
  - [sjPlot](https://cran.r-project.org/package=sjPlot)
  - [Rgitbook](https://github.com/jbryer/Rgitbook)
  - [table1xls](http://cran.r-project.org/web/packages/table1xls/index.html)
    Summary tables in Excel
    format.
  - [DescTools](http://cran.r-project.org/web/packages/DescTools/index.html)
  - [rctrack](http://www.stjuderesearch.org/site/depts/biostats/rctrack)

## Parallelisation & Big Data

Check also [CRAN Task View on High Performance
Computing](http://cran.r-project.org/web/views/HighPerformanceComputing.html).

  - [ff](https://cran.r-project.org/package=ff) Big data management. See
    also package `ffbase`
  - [batch](https://cran.r-project.org/package=batch) Batching routines
    in parallel
  - [bigdata](https://cran.r-project.org/package=bigdata)

## Niche & Species Distribution Modelling

  - [rgbif](https://cran.r-project.org/package=rgbif) Access to GBIF
    data
  - [spocc](https://cran.r-project.org/package=spocc) Species occurrence
    data retrieval and mapping
  - [dismo](https://cran.r-project.org/package=dismo) Distribution
    modelling
  - [SDMTools](http://www.rdocumentation.org/packages/SDMTools)
  - [adehabitatHS](http://cran.r-project.org/web/packages/adehabitatHS/index.html)
  - [biomod2](https://cran.r-project.org/package=biomod2) SDM ensembles
  - [hSDM](https://cran.r-project.org/package=hSDM) Bayesian SDM
  - [maxlike](https://cran.r-project.org/package=maxlike) SDM for
    presence-only data
  - [MigClim](https://cran.r-project.org/package=MigClim) Implements
    dispersal in SDMs
  - [GRaF](https://cran.r-project.org/package=GRaF) SDM using latent
    Gaussian random
    fields
  - [SightabilityModel](https://cran.r-project.org/package=SightabilityModel)
  - [EnvNicheR](https://cran.r-project.org/package=EnvNicheR)
  - [RinSp](http://cran.r-project.org/web/packages/RInSp/) Ecological
    niche metrics to measure individual specialization
  - [bdvis](https://github.com/vijaybarve/bdvis) Biodiversity data
    visualization
  - [phyloclim](https://cran.r-project.org/package=phyloclim) Includes
    functions for calculating niche overlap
  - [phylospacer](https://cran.r-project.org/package=phylospacer)
    Phyloclimates and
    phylomorphospaces
  - [PresenceAbsence](https://cran.r-project.org/package=PresenceAbsence)
  - [mboost](https://cran.r-project.org/package=mboost) Decomposing
    environmental, spatial, and spatiotemporal components of species
    distributions (Hothorn et al. 2011 Ecol Monogr)
  - [usdm](http://www.rdocumentation.org/packages/usdm) Uncertainty
    analysis for species distribution models, esp. focused on positional
    uncertainty
  - [ModelMap](http://cran.r-project.org/web/packages/ModelMap/) Random
    Forest and Stochastic Gradient Boosting Models
  - [modEVA](http://modtools.wordpress.com)
  - [rangemapper](https://cran.r-project.org/package=rangemapper)
  - [comclim](http://cran.r-project.org/web/packages/comclim/index.html)
    Community climate
    statistics
  - [hypervolume](http://cran.r-project.org/web/packages/hypervolume/index.html)
    Modeling hypervolumes (species’ niches)
  - [ppmlasso](https://cran.r-project.org/package=ppmlasso) Point
    process models
  - [sdmvspecies](https://cran.r-project.org/package=sdmvspecies) Create
    virtual species for SDM
  - [virtualspecies](http://borisleroy.com/virtualspecies/) Create
    virtual species
  - [coenocline](https://cran.r-project.org/package=coenocline) Simulate
    species presence and abundance along environmental gradients
  - [ecospat](http://cran.r-project.org/web/packages/ecospat/index.html)
    Many useful functions for niche & SDM (by A. Guisan’s group)
  - [comclim](https://cran.r-project.org/package=comclim)
  - [Metadata](https://cran.r-project.org/package=Metadata)
  - [ENiRG](http://cran.r-project.org/web/packages/ENiRG/index.html)

### Occupancy modelling

  - [detect](https://cran.r-project.org/package=detect) Occupancy
    modelling
  - [marked](https://cran.r-project.org/package=marked)
  - [unmarked](https://cran.r-project.org/package=unmarked)
  - [stocc](https://cran.r-project.org/package=stocc) Occupancy modeling
  - [hierarchicalDS](https://cran.r-project.org/package=hierarchicalDS)
    hierarchical analysis of distance sampling
    data

## Remote Sensing

  - [RStoolbox](https://github.com/bleutner/RStoolbox)
  - [moveVis](https://github.com/16EAGLE/moveVis)
  - [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR)
  - [rsMove](https://github.com/RRemelgado/rsMove)
  - [satellite](https://github.com/environmentalinformatics-marburg/satellite)
  - [satelliteTools](https://github.com/environmentalinformatics-marburg/satelliteTools)
  - [uavRst](https://github.com/gisma/uavRst)
  - [fieldRS](https://github.com/RRemelgado/fieldRS)
  - [cropPhenology](https://github.com/SofanitAraya/CropPhenology)
  - [rTIMESAT](https://github.com/kongdd/rTIMESAT)
  - [luna](https://github.com/rspatial/luna)
  - [rabbiTS](https://github.com/16EAGLE/rabbiTS)
  - [theiaR](https://github.com/norival/theiaR)
  - [sentinel2](https://github.com/IVFL-BOKU/sentinel2)
  - [getSpatialData](https://github.com/16EAGLE/getSpatialData)
  - [sen2r](https://github.com/ranghetti/sen2r)
  - [S2utils](https://github.com/bbrede/S2utils)
  - [SentinelAPI](https://github.com/mattjbayly/SentinelAPI)
  - [RGISTools](https://github.com/spatialstatisticsupna/RGISTools)

## Climate

  - [BerkeleyEarth](http://cran.r-project.org/web/packages/BerkeleyEarth/index.html)
    Climate data from Berkeley Earth database
  - [climates](https://cran.r-project.org/package=climates) Tools for
    climate data (bioclim, downscaling, interpolation…)
  - [climatol](https://cran.r-project.org/package=climatol)
    Homogenisation of climate time series
  - [climstats](https://cran.r-project.org/package=climstats) Tools for
    climate data
  - [RMAWGEN](https://cran.r-project.org/package=RMAWGEN) Generate daily
    time series from monthly mean values
  - [climdex.pcic](https://cran.r-project.org/package=climdex.pcic)
    Computation of climate
    indices
  - [ClimClass](http://cran.r-project.org/web/packages/ClimClass/index.html)
    Climate Classification according to various indices
  - [RClimMAWGEN](https://cran.r-project.org/package=RClimMAWGEN)
    generate time series of climate indices
  - [chillR](https://cran.r-project.org/package=chillR) Climate and
    phenology analysis
  - [rWBclimate](https://cran.r-project.org/package=rWBclimate) Lots of
    historical data and future projections
  - [rnoaa](https://cran.r-project.org/package=rnoaa)
  - [rghcnV3](https://cran.r-project.org/package=rghcnV3) GHCN
  - [RNCEP](https://cran.r-project.org/package=RNCEP) weather data
  - [sirad](https://cran.r-project.org/package=sirad) Evapotranspiration
    etc
  - [SPEI](https://cran.r-project.org/package=SPEI) Calculates
    Standardised Precipitation-Evaporation Index
  - [SPI](https://cran.r-project.org/package=SPI)
  - [weathermetrics](https://cran.r-project.org/package=weathermetrics)
  - [raincpc](https://cran.r-project.org/package=raincpc) Rainfall
    data
  - [Evapotranspiration](http://cran.r-project.org/web/packages/Evapotranspiration/index.html)
  - [GhcnDaily](http://cran.r-project.org/web/packages/GhcnDaily/index.html)
  - [crn](http://cran.r-project.org/web/packages/crn/index.html) Get
    data from Climate Reference
    Network
  - [iki.dataclim](http://cran.r-project.org/web/packages/iki.dataclim/index.html)
  - [FedData](http://cran.r-project.org/web/packages/FedData/index.html)
  - [stationaRy](https://github.com/rich-iannone/stationaRy) Hourly data
    worldwide
  - [tempcyclesdata](https://cran.r-project.org/web/packages/tempcyclesdata/index.html)
    Temperature data for ca. 8000 stations 1975-2013

## GIS/spatial functionality

Check also CRAN Task View on
[Spatial](http://cran.r-project.org/web/views/Spatial.html) and
[Spatiotemporal](http://cran.r-project.org/web/views/SpatioTemporal.html)
data. Check also CRAN Task View on [Web
technologies](http://cran.r-project.org/web/views/WebTechnologies.html)
for access to many GIS data.

  - [sp](https://cran.r-project.org/package=sp)

  - [spacetime](https://cran.r-project.org/package=spacetime)

  - [spatial](https://cran.r-project.org/package=spatial)

  - [rgeos](https://cran.r-project.org/package=rgeos)

  - [rgdal](https://cran.r-project.org/package=rgdal)

  - [raster](https://cran.r-project.org/package=raster)

  - [rasterVis](https://cran.r-project.org/package=rasterVis)

  - [rts](https://cran.r-project.org/package=rts) Raster time series

  - [spatial.tools](https://cran.r-project.org/package=spatial.tools)
    Functions for raster processing, including parallel processing

  - [maptools](https://cran.r-project.org/package=maptools) Reading and
    manipulating geographic data

  - [PBSmapping](https://cran.r-project.org/package=PBSmapping)

  - [taRifx.geo](https://cran.r-project.org/package=taRifx.geo) Useful
    spatial functions

  - [climstats](https://cran.r-project.org/package=climstats) Tools for
    climate and raster analyses

  - [countrycode](https://cran.r-project.org/package=countrycode)
    Converts country codes

  - [cshapes](https://cran.r-project.org/package=cshapes) Dataset of
    country boundaries

  - [gdistance](https://cran.r-project.org/package=gdistance) Calculate
    distances and routes on grids

  - [geometry](https://cran.r-project.org/package=geometry) Mesh
    generation and surface tesselation

  - [geosphere](https://cran.r-project.org/package=geosphere) Several
    GIS tools, esp. aimed at large scales (global)

  - [geonames](https://cran.r-project.org/package=geonames)

  - [mapproj](https://cran.r-project.org/package=mapproj) Converts
    lat-lon data into projected coordinates

  - [geospacom](https://cran.r-project.org/package=geospacom) Generates
    distance matrices from shape files and represents spatially weighted
    multilevel analysis results

  - [dismo](https://cran.r-project.org/package=dismo)

  - [fossil](https://cran.r-project.org/package=fossil)

  - [ggmap](https://cran.r-project.org/package=ggmap) Plotting on Google
    Maps and OpenStreetMap

  - [GISTools](https://cran.r-project.org/package=GISTools) Some further
    GIS tools (e.g. cloropleth maps)

  - [mapplots](https://cran.r-project.org/package=mapplots) Data
    visualisation on maps

  - [maps](https://cran.r-project.org/package=maps) Mapping tools

  - [OpenStreetMap](https://cran.r-project.org/package=OpenStreetMap)
    Access to OpenStreetMap and Bing images

  - [osmar](https://cran.r-project.org/package=osmar)

  - [plotGoogleMaps](https://cran.r-project.org/package=plotGoogleMaps)

  - [RgoogleMaps](https://cran.r-project.org/package=RgoogleMaps)

  - [R2G2](https://cran.r-project.org/package=R2G2) Plot anything in
    Google Earth

  - [rCarto](https://cran.r-project.org/package=rCarto) useful functions
    for mapping

  - [marmap](https://cran.r-project.org/package=marmap) working with
    bathymetric and topographic data

  - [plotKML](https://cran.r-project.org/package=plotKML) Visualization
    of spatial and spatio-temporal objects in Google Earth

  - [MODISTools](http://cran.r-project.org/web/packages/MODISTools/)

  - [spGoogle](http://cran.r-project.org/web/packages/spGoogle)
    Interacting R with Google maps

  - [rMaps](https://cran.r-project.org/package=rMaps) Interactive maps

  - [leafletR](https://cran.r-project.org/package=leafletR)

  - [GEOmap](https://cran.r-project.org/package=GEOmap)

  - [rworldmap](https://cran.r-project.org/package=rworldmap)

  - [choroplethr](https://cran.r-project.org/package=choroplethr)

  - [mapmisc](http://cran.r-project.org/web/packages/mapmisc/index.html)
    Utilities for producing maps

  - [sinkr](https://github.com/menugget/sinkr) Some GIS functions and
    colour palettes

  - [rlandscape](https://cran.r-project.org/package=rlandscape)
    Generates spatial landscapes

  - [RSAGA](https://cran.r-project.org/package=RSAGA)

  - [spgrass6](https://cran.r-project.org/package=spgrass6)

  - [spsextante](https://cran.r-project.org/package=spsextante)

  - [RPyGeo](https://cran.r-project.org/package=RPyGeo)

## Spatial Analysis

Check also CRAN Task View on
[Spatial](http://cran.r-project.org/web/views/Spatial.html) and
[Spatiotemporal](http://cran.r-project.org/web/views/SpatioTemporal.html)
data.

  - [akima](https://cran.r-project.org/package=akima) Interpolation
  - [automap](https://cran.r-project.org/package=automap) Automatic
    interpolation (kriging)
  - [ecespa](https://cran.r-project.org/package=ecespa) Point pattern
    analysis
  - [fields](https://cran.r-project.org/package=fields) Splines,
    kriging, etc
  - [geoR](https://cran.r-project.org/package=geoR) Geostatistical
    analysis
  - [geoRglm](https://cran.r-project.org/package=geoRglm) Spatial GLMs
  - [geospt](https://cran.r-project.org/package=geospt) Geostatistics
  - [GeoXP](https://cran.r-project.org/package=GeoXP) Interactive
    exploratory analysis of spatial data
  - [gstat](https://cran.r-project.org/package=gstat) Geostatistics
    (variograms, kriging)
  - [intamap](https://cran.r-project.org/package=intamap) Automatic
    spatial interpolation
  - [geostatsp](https://cran.r-project.org/package=geostatsp)
    Geostatistics using SpatialPoints and rasters
  - [spatstat](https://cran.r-project.org/package=spatstat)
  - [spBayes](https://cran.r-project.org/package=spBayes)
  - [spdep](https://cran.r-project.org/package=spdep) Modeling spatial
    dependence
  - [stpp](https://cran.r-project.org/package=stpp) Point patterns
  - [rtop](https://cran.r-project.org/package=rtop) Spatial
    interpolation of data

## Networks

  - [bipartite](https://cran.r-project.org/package=bipartite)
  - [igraph](https://cran.r-project.org/package=igraph) Network analysis
    and visualization
  - [enaR](https://cran.r-project.org/package=enaR)
  - [qgraph](https://cran.r-project.org/package=qgraph)

## Phylogenetics, phylogeography & comparative analysis

Check also [Phylogenetics CRAN task
view](http://cran.r-project.org/web/views/Phylogenetics.html).

  - [ape](https://cran.r-project.org/package=ape)
  - [adephylo](http://cran.r-project.org/web/packages/adephylo/index.html)
    Exploratory analysis
  - [Treesim]() Tree simulation. See also
    [treesimGM](https://cran.r-project.org/package=Treesim%5D\(\)%20Tree%20simulation.%20See%20also%20%5BtreesimGM)
  - [cladoRcpp](https://cran.r-project.org/package=cladoRcpp)
    Phylogenetic analysis of geographic ranges
  - [caper](https://cran.r-project.org/package=caper) Comparative
    analysis
  - [PVR](https://cran.r-project.org/package=PVR) Phylogenetic
    Eigenvector Regression
  - [BEDASSLE](http://cran.r-project.org/web/packages/BEDASSLE/)
    Disentangles the effects of geographic and ecological isolation on
    genetic differentiation
  - [geiger](https://cran.r-project.org/package=geiger)
  - [geoscale](https://cran.r-project.org/package=geoscale) Geological
    timescale
  - [phangorn](https://cran.r-project.org/package=phangorn)
  - [phytools](https://cran.r-project.org/package=phytools)
  - [pegas](https://cran.r-project.org/package=pegas)
  - [picante](https://cran.r-project.org/package=picante)
  - [stratigraph](https://cran.r-project.org/package=stratigraph)
  - [treebase](https://cran.r-project.org/package=treebase)
  - [MCMCglmm](https://cran.r-project.org/package=MCMCglmm)

## Palaeoecology

  - [Bchron](https://cran.r-project.org/web/packages/Bchron/index.html)
    Bayesian chronologies
  - [Bclim](https://cran.r-project.org/web/packages/Bclim/index.html)
    Palaeoclimate reconstruction

## Dendrochronology

  - [dplR](https://github.com/cran/dplR) Dendrochronology
  - [measuRing](https://github.com/cran/measuRing) Measuring ring width
    from scanned images.  
  - [TRADER](https://github.com/pavel-fibich/TRADER) Tree Ring Analysis
    of Disturbance Events  
  - [dendrobox](https://github.com/cszang/dendrobox) Interactive
    Tree-Ring Data Exploration Tool  
  - [treeclim](https://github.com/cszang/treeclim) Modeling tree-climate
    relationships.  
  - [bootRes](https://github.com/cszang/bootRes) Bootstrapped response
    functions.  
  - [rwtocore](https://github.com/ltrr-arizona-edu/rwtocore) convert
    tree-ring measurements to drawings of cores (Ruby).
  - [triforce](https://github.com/ltrr-arizona-edu/triforce) read the
    TRiDaS dendrochronological standard and communicate with Tellervo
    servers.
  - [pointRes](https://cran.r-project.org/web/packages/pointRes/index.html)
    Calculate and plot pointer years
  - [BIOdry](https://cran.r-project.org/web/packages/BIOdry/index.html)
    Multilevel Modeling of Dendroclimatical Fluctuations
  - [sclero](https://cran.r-project.org/web/packages/sclero/) Measure
    Growth Patterns and Align Sampling Spots in Photographs
  - [dendrometeR](https://cran.r-project.org/web/packages/dendrometeR/)
    Analyzing Dendrometer Data.
  - [wvtool](https://cran.r-project.org/package=wvtool) Image Tools for
    Automated Wood
    Identification
  - [DendroSync](https://cran.r-project.org/web/packages/DendroSync/index.html)
    Calculating Spatial Synchrony Between Tree-Ring Chronologies
  - [iadf](https://cran.r-project.org/web/packages/iadf/index.html)
    Analysis of Intra Annual Density Fluctuations
  - [dendroExtra](https://cran.r-project.org/package=dendroExtra) Finds
    the optimal sequence of days that are linearly or nonlinearly
    related to one or more tree-ring proxy records.

## Ecological analyses (miscellaneous)

Check also [Environmetrics CRAN Task
View](http://cran.r-project.org/web/views/Environmetrics.html).

  - [betapart](https://cran.r-project.org/package=betapart) Beta
    diversity
  - [BiodiversityR](https://cran.r-project.org/package=BiodiversityR)
    GUI for biodiversity, suitability and community ecology analyses
  - [cheddar](https://cran.r-project.org/package=cheddar) Analysis and
    visualisation of community data
  - [coexist](https://cran.r-project.org/package=coexist) Modelling
    species coexistence
  - [DSpat](https://cran.r-project.org/package=DSpat) Distance Sampling
  - [fossil](https://cran.r-project.org/package=fossil) Species
    richness, species-area curves, beta-diversity
  - [indicspecies](https://cran.r-project.org/package=indicspecies)
    Assess associations between different species and sites
    (e.g. indicator species)
  - [IPMpack](https://cran.r-project.org/package=IPMpack) Integral
    Projection Models
  - [marked](https://cran.r-project.org/package=marked) Mark-recapture
    analysis
  - [MBI](https://cran.r-project.org/package=MBI) Multiple Beta
    Diversity indices
  - [rmeta](https://cran.r-project.org/package=rmeta) Meta-analysis
  - [neighlikeli](https://cran.r-project.org/package=neighlikeli)
    Neighborhood models
  - [earlywarnings](https://cran.r-project.org/package=earlywarnings)
  - [MAR1](https://cran.r-project.org/package=MAR1) Multivariate
    Autoregressive Modeling for Analysis of Community Time-Series Data
  - [ncbit](https://cran.r-project.org/package=ncbit) retrieve NBCI
    taxonomic data
  - [spacodiR](https://cran.r-project.org/package=spacodiR) Spatial and
    Phylogenetic Analysis of Community Diversity
  - [Reol](http://cran.r-project.org/web/packages/Reol/) Interface to
    Encyclopedia of Life
  - [SPECIES](https://cran.r-project.org/package=SPECIES) Species
    richness and diversity analysis
  - [BayesComm](https://cran.r-project.org/package=BayesComm) Bayesian
    multivariate binary regression models for analysis of ecological
    communities
  - [pom](https://cran.r-project.org/package=pom) Patch occupancy models
  - [capwire](https://cran.r-project.org/package=capwire) Population
    size estimation from non-invasive sampling
  - [vegclust](https://cran.r-project.org/package=vegclust) Fuzzy
    clustering of vegetation data
  - [popbio](https://cran.r-project.org/package=popbio)
  - [demoniche](http://demoniche.r-forge.r-project.org/)
    Spatially-explicit demographic modelling
  - [BEDASSLE](https://cran.r-project.org/package=BEDASSLE) Disentangles
    the effects of geographic and ecological isolation on genetic
    differentiation.
  - [rphylopic](https://github.com/sckott/rphylopic) Organisms
    silhouettes
  - [GSIF](https://cran.r-project.org/package=GSIF) Global Soil
    Information
  - [Rarity](https://cran.r-project.org/package=Rarity) Rarity indices
  - [taxize](https://cran.r-project.org/package=taxize) Taxonomy etc.
  - [Taxonstand](https://cran.r-project.org/package=Taxonstand)
  - [sExtinct](https://cran.r-project.org/package=sExtinct) Extinction
    analysis based on sightings
  - [BEDASSLE](http://cran.r-project.org/web/packages/BEDASSLE/)
    Disentangles the effects of geographic and ecological isolation on
    genetic differentiation
  - [ecomodtools](https://cran.r-project.org/package=ecomodtools)
    Simulation models (inc. dispersal)
  - [comclim](http://cran.r-project.org/web/packages/comclim/index.html)
    Community climate
    statistics
  - [kernelPop](http://cran.r-project.org/web/packages/kernelPop/index.html)
    Spatially explicit population genetic simulations
  - [siplab](http://cran.r-project.org/web/packages/siplab/index.html)
    spatially explicit individual-based vegetation models.

## Miscellaneous

  - [digitize](https://cran.r-project.org/package=digitize) Extract data
    from plots
  - [downloader](https://cran.r-project.org/package=downloader) Download
    files from internet
  - [hwriter](https://cran.r-project.org/package=hwriter) Outputs R
    objects in HTML format
  - [installr](https://cran.r-project.org/package=installr)
    Automatically update R
  - [mail](https://cran.r-project.org/package=mail) Send email
    notifications from R
  - [sendmailR](https://cran.r-project.org/package=sendmailR)
  - [mosaic](https://cran.r-project.org/package=mosaic)
  - [audiolyzR](https://cran.r-project.org/package=audiolyzR) Creates
    audio representations of common plots
  - [WebDevelopR](https://cran.r-project.org/package=WebDevelopR) Web
    development
  - [ProjectTemplate](https://cran.r-project.org/package=ProjectTemplate)
  - [gpk](https://cran.r-project.org/package=gpk) Datasets for
    educational
    uses
  - [NCmisc](http://cran.r-project.org/web/packages/NCmisc/)
  - [PubMedWordcloud](https://cran.r-project.org/package=PubMedWordcloud)
    Create wordcloud with abstracts.
  - [alm](https://cran.r-project.org/package=alm) Altmetrics
  - [rAltmetric](https://cran.r-project.org/package=rAltmetric)
    Retrieves data from altmetrics.com
  - [RMendeley](https://cran.r-project.org/package=RMendeley)
  - [rcrossref](https://cran.r-project.org/package=rcrossref)
  - [RefManageR](https://cran.r-project.org/package=RefManageR)
    Bibliography Management.
  - [refnet](https://cran.r-project.org/package=refnet) Reads and works
    with data from ISI Web of Knowledge
  - [scholar](https://cran.r-project.org/package=scholar)
  - [slidify](https://cran.r-project.org/package=slidify)
  - [sos](https://cran.r-project.org/package=sos) Search R
    packages
  - [source.gist](https://cran.r-project.org/package=source.gist)
  - [twitteR](https://cran.r-project.org/package=twitteR)
  - [DescTools](http://cran.r-project.org/web/packages/DescTools/index.html)

## R programming

  - [codetools](https://cran.r-project.org/package=codetools) Code
    analysis tools
  - [compiler](https://cran.r-project.org/package=compiler) Compile R
    code (e.g. a function) to speed it up
  - [devtools](https://cran.r-project.org/package=devtools)
  - [formatR](https://cran.r-project.org/package=formatR) Format and
    tidy R code
  - [gtools](https://cran.r-project.org/package=gtools) Useful functions
    (e.g. mixedsort)
  - [inline](https://cran.r-project.org/package=inline) Define functions
    in C code within R
  - [iterators](https://cran.r-project.org/package=iterators) Tools for
    iteration on many different types of objects (see also `itertools`)
  - [Kmisc](https://cran.r-project.org/package=Kmisc) Data reshaping,
    table and plot generation from RMarkdown
  - [operators](https://cran.r-project.org/package=operators) Additional
    operators
  - [simFrame](https://cran.r-project.org/package=simFrame) A framework
    to work with simulations
  - [simSummary](https://cran.r-project.org/package=simSummary)
  - [staticdocs](https://cran.r-project.org/package=staticdocs) Create
    webpage with package documentation
  - [testit](https://cran.r-project.org/package=testit) Testing R
    packages
  - [testthat](https://cran.r-project.org/package=testthat) Testing R
    code
  - [tester](https://cran.r-project.org/package=tester) Test
    characteristics of R objects
  - [assertthat](https://cran.r-project.org/package=assertthat).
  - [httr](https://cran.r-project.org/package=httr) Working with URLs
    and HTTP
  - [RCurl](https://cran.r-project.org/package=RCurl) HTTP interface
  - [stringr](https://cran.r-project.org/package=stringr)
  - [Rd2Roxygen](https://cran.r-project.org/package=Rd2Roxygen)
  - [Rxoygen2](https://cran.r-project.org/package=Rxoygen2)
  - [scrapeR](https://cran.r-project.org/package=scrapeR)
  - [aprof](http://cran.r-project.org/web/packages/aprof/index.html)
    Profiling code and visualizing results to evaluate where is best to
    focus code optimization.
  - [regex](https://github.com/richierocks/regex) Regular expressions
    made easier.