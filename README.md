# About

This is an effort to create a general template for most projects

# Guidelines

## Data

- Be very mindful of anonymization especially when sharing data  

- Provide metadata about data. This can be in the form of codebooks, data dictionaries etc. where what each column/field contains (units, how the measure was derived, allowable values etc) is explained    

- Sharing guidelines:

> For shared research products to be usable by others, they should meet a set of standards known as ‘FAIR’: Findable, Accessible, Interoperable, and Reusable (Wilkinson et al., 2016). Findable products are easily discoverable to both humans and machines. That means linking to them in research reports using unique persistent identifiers (e.g. a digital object identifier [DOI]). and attaching them with meta-data describing what they are so they can be indexed by search engines. Accessibility means that research products need to be preserved across the long-term and are retrievable via their standardized identifier. Interoperability means that the research products needs to be in a format that people and machines (e.g., search engines and analysis software) can understand. Reusable means that the research products need to be well organized, documented, and licensed so that others know how to use them.

- Where to share: Zenodo, Figshare, the Open Science Framework (OSF), and the various Dataverse sites  

## Code

From ["Software Engineering Practices in Academia"](https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2)  
    
> Our experience from teaching data science is that the quality of a computation notebook is greatly improved by two practices. The first is documentation. All codes should have documentation that specifies: (i) what the function does, (ii) the types of arguments to the function, and (iii) the types of values returned by the function. A second consideration is to make sure that there is a test for each function, typically within the same cell as the function definition so that the test is run when the function is defined. A final consideration is when to move code from a notebook to a Python module (a file that has extension ‘.py’).  

# To resolve

- The minimal amount of library/package info

- Narrative overview of code and the order it is ought to be run in
    - Would a README be a good place to put that info? But one README per directory is unlikely to be enough

- What should the `run_all_analyses.R` script and its outputs look like?

- Different type of projects: e.g. theoretical/simulation based, meta-analyses

- Data version control
    - Do we want to use tools designed for ML https://neptune.ai/blog/best-data-version-control-tools
    - Or something that is more focused on research https://www.datalad.org/

- Linking files in raw_data to code/collection procedure that collected it in experiment
    - How about adding column to raw_data that contains at least the script name and preferably some sort of hash associated with the version experiment code script
    - What would this look like for the different methods we use e.g. Gorilla vs. Psychopy vs. Psychtoolbox etc.

# To do

- Keep this as the bare bones clone-able directory and populate with examples separately

- Sample codebook/data dictionary. Packages that automate this codebook, dataspice, and dataMaid (Arslan, 2019)

# Resources

[Chapter on project management from open textbook on Experimental Methods](https://experimentology.io/13-management)  

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
