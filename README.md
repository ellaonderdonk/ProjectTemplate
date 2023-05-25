This is an effort to create a general template for most projects

## Resources

https://experimentology.io/13-management  

[A practical guide for transparency in psychological science](https://psych-transparency-guide.uni-koeln.de/)

[The Practice of Reproducible Research: Case Studies and Lessons from the Data-Intensive Sciences](http://www.practicereproducibleresearch.org/)  

[Stanford CORES: Open By Design](https://dsi-cores.github.io/OpenByDesign/README.html)  
    - Brief descriptions with links to many resources  

[NASA: Transform to Open Science](https://nasa.github.io/Transform-to-Open-Science-Book/About/About-Announcements.html)  

[Easing Into Open Science: A Gudie for Graduate Students and their Advisors](https://psyarxiv.com/vzjdp/)
    - Short paper with step by step guide  

[TIER: Teaching Integrity in Empirical Reasearch](https://www.projecttier.org/)
    - Specifically the [protocol](https://www.projecttier.org/tier-protocol/protocol-4-0/)  
    - Lots of teaching materials as well  

## To be resolved

- The minimal amount of library/package info

- Narrative overview of code and the order it is ought to be run in
    - Would a README be a good place to put that info? But one README per directory is unlikely to be enough
- Naming of intermediate analysis notebooks
    - I typically go with something like `NB3_question_of_interest` and try to keep notebooks self-contained and small. The idea is to use the notebook to figure out how to do an analysis then the clean and functional code from the notebook would be placed into a final script that reproduces all the analyses for a submission (e.g. `run_all_analyses.R`).
    - From ["Software Engineering Practices in Academia"](https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2)
    ```
    Our experience from teaching data science is that the quality of a computation notebook is greatly improved by two practices. The first is documentation. All codes should have documentation that specifies: (i) what the function does, (ii) the types of arguments to the function, and (iii) the types of values returned by the function. A second consideration is to make sure that there is a test for each function, typically within the same cell as the function definition so that the test is run when the function is defined. A final consideration is when to move code from a notebook to a Python module (a file that has extension ‘.py’).
    ```
- What should the `run_all_analyses.R` script and its outputs look like?

- Test writing for scripts
    - Where do tests fit in when exploring/figuring out how to do something like in notebooks?

- Different type of projects: e.g. theoretical/simulation based, meta-analyses

- Sample codebook/data dictionary. Packages that automate this codebook, dataspice, and dataMaid (Arslan, 2019)

- Reconsider where to share data (see experimentology chapter 13 for why)

- What to put in a general .gitignore
- Data version control
    - Linking files in raw_data to code/collection procedure that collected it in experiment

- Keep this as the bare bones clone-able directory and populate with examples separately