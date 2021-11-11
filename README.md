
# Yi Lab analysis resources

This page aims to introduce Yi lab members to basic statistics, basic programming in R/Python, and classic pipelines for biological data analysis with a focus on single-cell data.

At this time, I will not include any of my own code. Instead, I plan to deposit my code for different projects in a way that we can later include the link to the corresponding repository in the paper as part of our effort to promote reproducible science. This is to be said, for now, I will only list tutorials put together by other people.  Even though people have asked me to include some comments on popular tutorials (e.g. Seurat), personally I found comments in those popular tutorials are very detailed and already more than enough (and, if you don't read their comments, probably you won't read mine either). Moreover, who else can be more qualified than the developer themselves to tell people the best practice for using the packages?

However, I do acknowledge that it could be overwhelming for people new to programming to get started. So here are some of my tips for beginners:

* First thing first, learn the language 
    * You know, nobody will understand Shakespeare without knowing the alphabet

* Understand some basic statistics
    * Although not necessary, I believe this will help us better understand how a function works and hence the best way to use it

* DO NOT just copy the code and run with your own data
    * After installing any package, follow the tutorials and run on the same data as in their demo and make sure you can replicate their analysis
    * READ THEIR COMMENTS. Try to understand what each step/function does and why they choose to use certain parameters
    * When in doubt, always refer back to the paper
    * When getting errors, check the "Issues" section of their Github page to see if anyone else encountered the same issue and how they solved it. If it's a new issue, consider asking for help by opening a new issue 

* Let google become your bestie
    * For questions like which function to use or what's the specific syntax in a programming language, Google will surprise you with how much she knows

* Last but not the least, believe in yourself & be patient to yourself
    * There's indeed a learning curve for dry lab analysis, so give yourself chances to have some trial-and-error attempts

With some good approaches and a developing mindset, I believe we all can quantitatively make sense of our data and generative easily interpretable visualization by some lines of code. No further ado, let's get started:)


## R/Python

* R/Python Fundamentals Bootcamp and more offered by NU IT: https://www.eventbrite.com/o/northwestern-it-research-computing-services-7958795297
* Dataquest Online Courses (Can request free access for NU researchers): https://www.it.northwestern.edu/research/campus-events/data-camp.html

## Basic Stats, Math, & ML

* YouTube channel -- **StatQuest**: https://www.youtube.com/c/joshstarmer
* YouTube channel --  **3Blue1Brown**: https://www.youtube.com/c/3blue1brown
* Book -- **Statistics Using R with Biological Examples**: https://cran.r-project.org/doc/contrib/Seefeld_StatsRBio.pdf
* Book -- **An Introduction to Statistical Learning**: https://www.statlearning.com/


## Some popular packages for SC analysis

* **From Rahul Satija lab** (R-based)
    * Package **Seurat** (Basic analysis pipeline for scRNA-seq)
        * Papers: https://doi.org/10.1038/nbt.3192; https://doi.org/10.1038/nbt.4096; https://doi.org/10.1016/j.cell.2019.05.031; https://doi.org/10.1016/j.cell.2021.04.048 
        * Tutorials: https://satijalab.org/seurat/articles/get_started.html
    * Package **Signac** (Basic analysis pipelien for scATAC-seq/scCUT&Tag)
        * Paper: https://doi.org/10.1038/s41592-021-01282-5
        * Tutorials: https://satijalab.org/signac/articles/overview.html
* **From Cole trapnell** lab (R-based)
    * Package **Monocle** (Pseudotime/trajectory analysis for scRNA-seq)
        * Papers: https://doi.org/10.1038/nbt.2859; https://doi.org/10.1038/nmeth.4402; https://doi.org/10.1038/nmeth.4150 
        * Tutorials: https://cole-trapnell-lab.github.io/monocle3/docs/introduction/
    * Package **Cicero** (co-accessibility analysis for scATAC-seq)
        * Papers: http://doi.org/10.1016/j.molcel.2018.06.044
        * Tutorials: https://cole-trapnell-lab.github.io/cicero-release/docs_m3/
* **From Fabian Theis lab** (Python-based)
    * Module **Scanpy** (Basic analysis pipeline for scRNA-seq)
        * Paper: https://doi.org/10.1186/s13059-017-1382-0
        * Tutorials: https://scanpy.readthedocs.io/en/stable/index.html
    * Function **PAGA** (available within Scanpy for connectivity and trajectory analysis)
        * Paper: https://doi.org/10.1186/s13059-019-1663-x
        * Tutorials: https://scanpy-tutorials.readthedocs.io/en/latest/paga-paul15.html
    * Module **scVelo** (RNA velocity and dynamics analysis)
        * Papers: https://doi.org/10.1038/s41586-018-0414-6; https://doi.org/10.1038/s41587-020-0591-3
        * Tutorials: https://scvelo.readthedocs.io/getting_started/
## Other resourses

* Seruat command list: https://satijalab.org/seurat/articles/essential_commands.html
* Graphing in R with Plotly: https://plotly.com/r/
* R color cheatsheet: https://www.nceas.ucsb.edu/sites/default/files/2020-04/colorPaletteCheatsheet.pdf
* ggplot2 cheatsheet: https://www.maths.usyd.edu.au/u/UG/SM/STAT3022/r/current/Misc/data-visualization-2.1.pdf
* dplyr & tidyr cheatsheet: https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf
* STHDA: http://www.sthda.com/english/wiki/wiki.php
