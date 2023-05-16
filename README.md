This is an effort to create a general template for most projects

## Resources

https://experimentology.io/13-management  
http://www.practicereproducibleresearch.org/  
https://poldracklab.github.io/research/research.html  
https://dsi-cores.github.io/OpenByDesign/README.html  
https://science.nasa.gov/open-science/transform-to-open-science  


## To be resolved

- The minimal amount of library/package info
- More harmony across different data types (e.g. behavior, eyetracking and fmri directory structures can be more similar)
- Narrative overview of code and the order it is ought to be run in
    - Would a README be a good place to put that info? But one README per directory is unlikely to be enough
- Naming of intermediate analysis notebooks
- What should the `run_all_analyses.R` script and its outputs look like?
- Matlab style function saving `function.m` or defining within bigger scripts?
- Test writing for scripts
- Different type of projects: e.g. theoretical/simulation based, meta-analyses
- Tracking changes in data (from raw to processed)
- Connecting figures to scripts that generated them
    - Editing image meta-data with the code/script that generated it
- Linking files in raw_data to code/collection procedure that collected it in experiment
- Sample codebook/data dictionary. Packages that automate this codebook, dataspice, and dataMaid (Arslan, 2019)
- Reconsider where to share data (see experimentology chapter 13 for why)
